# Execution Service
Wednesday, May 4, 2016
1:02 PM

## Main Objectives:

## Development:

1.	Get the PaaS (Management Portal) working with the initial version of the Execution Service

    [http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168407](http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168407)

    1.  Putting the execution service code in the depo
    2.  Getting the current PaaS working with the Execution Service
            1.	Remove dependencies on file paths (replace with file contents) wherever necessary
            2.	Remove usage of PS Credentials (replace with Credential Result)
            3. 	Change the deployment script to also deploy the execution service
            4.  Basic monitoring on the execution service
            5.  Make the final necessary changes for the PaaS to use the Execution Service instead of the PowerShell runner

2.	Make the portal resilient against NST crashes

    [http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168408](http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168408)
    1.  Make the Tables have a BEGIN and END method, which modify statuses accordingly (depending on how the PowerShell commands executed) (for example, BeginProvision would call Begin, return an ExecServiceOperationID and, EndProvision would poll that operationID and call End once it is done)
    2.  Replace the background session with a Job Queue entry (or something similar) that queries the statuses of the Execution Requests

3.	Replacing all of the relevant cmdlets to use the Execution Service instead of the PowerShell runner.

    [http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168409](http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168409)
    a.	Identify which cmdlets are worth transitioning to C#
    b.	Replace them one by one (and convert them into Microservices)

4.	Open the Management Endpoint and ensure that the NAV management dll is removed from PaaS (can be independent from the other objectives)

    [http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168410](http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168410)
    1.	Make the management endpoint accept other kinds of authentication, in addition to Windows Credentials
    2.	Making the endpoint available
    3.	Create a wrapper for the endpoint
    4.	Update the PaaS code to make use of the wrapper instead of the actual NAV mgmt cmdlets
    5.	Remove the mgmt dll and dependent assemblies from our scripts

5.	Measurement (especially useful for the leadership team)

    [http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168411](http://vstfnav:8080/tfs/web/wi.aspx?pcguid=9a2ffec1-5411-458b-b788-8c4a5507644c&id=168411)
    
    (there are 2 things we want to measure all throughout the development process - speed and scalability)
    1.	Determine a way to measure the speed
    2. 	Determine a way to measure the scalability (can be the delta between the minimum and maximum resource creation/provisioning times, given that usually the system is more heavily loaded towards the end of the process, or see how other companies are doing it, for example)
    3.	Measure the behavior of the product in a long-running stressful scenario
    4.	Determine the new values of those metrics for the 'final' version of the product

# Trace a Route

🔎<b>Objectives</b>

- Determine network connectivity to a destination host
- Trace a route to a remote server using tracert
<h1></h1>

The tracert command allow you to trace the amount of hops aken for a source to a destination. 


<b>Step 1: Determine Network Connectivity to a Destination Host</b>

Navigate to the Command Prompt, enter <b>ping www.facebook.com</b> to determine if it is reachable.
Now ping one of the Regional Internet Registry (RIR) websites located in different parts of the world to determine if it is reachable:

  
         Australia:             www.apnic.net

         South America:         www.lacnic.net

         North America:         www.arin.net
        
<p align="center">
<img src="Screenshot (80).png"/>
</p>

<b>Step 2: Trace a route to a remote server with [tracert](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/tracert)</b>

Each hop in the tracert results displays the routes that the packets take when traveling to the final destination.  When the final destination is reached, an ICMP echo reply is sent to the source host.

  <b>Step 3:</b>
 Trace the route to www.apple.com
 
 <p align="center">
<img src="Screenshot (81).png"/>
</p>
 

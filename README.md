# java-lab-10-solved
**TO GET THIS SOLUTION VISIT:** [Java Lab 10 Solved](https://www.ankitcodinghub.com/product/java-lab-10-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95435&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Java Lab 10 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Networking

Create an application where clients connect to a server in order to form a social network. The application will contain two parts (create a project for each one):

<ul>
<li>The server is responsible with the management of the clients and the implementation of the services.</li>
<li>The client will communicate with the server, sending it commands containing the name of the service and the required parameters. The commands are:</li>
</ul>
o register name: adds a new person to the social network;

o login name: establishes a connection between the server and the client; o friend name1 name2 … namek: adds friendship relations between the

person that sends the command and other persons; o send message: sends a message to all friends.

o read: reads the messages from the server.

The main specifications of the application are: Compulsory (1p)

<ul>
<li>Create the project for the server application.</li>
<li>Implement the class responsible with the creation of a ServerSocket running at
a specified port. The server will receive requests (commands) from clients and

it will execute them.
</li>
<li>Create a class that will be responsible with communicating with a client Socket.
The communication will be on a separate thread. If the server receives the command stop it will stop and will return to the client the respons “Server stopped”, otherwise it return: “Server received the request … “.
</li>
<li>Create the project for the client application.</li>
<li>A client will read commands from the keyboard and it will send them to the
server. The client stops when it reads from the keyboard the string “exit”. Optional (2p)
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>Create an object-oriented model for your application and implement the commands.
The command stop should “gracefully” stop the server – it will not accept new games but it will finish those in progress. When there are no more games, it will shutdown.
</li>
<li>Implement a timeout for a connection (a number of minutes). If the server does not receive any command from a logged in client in the specified period of time, it will terminate the connection.</li>
<li>Create an HTML embeddable representation of the social network using JFreeChart, JGraphT and Apache Batik, or other technology.</li>
<li>Upload the HTML representation directly from the application to a Web server. You may use JCraft for connecting to a server using SFTP and transferring a file (or a similar solution).
Bonus (2p)
</li>
</ul>
<ul>
<li>Implement an algorithm to determine the structural cohesion of the network.</li>
<li>Rewrite the application so it can act both as a server or a client, depending on
circumstances.

Suppose that the clients (agents) are inside an intranet and their IP addresses are known (or within a known limited range).

Implement a leader election algorithm such that, if the server (the coordinator agent) fails, one of the other agents “elects” itself as the coordinator of the network and the communication can still continue.

Resources
</li>
</ul>
<ul>
<li>Custom Networking</li>
<li>Remote Method Invocation (RMI)</li>
<li>Java Networking
Objectives
</li>
</ul>
<ul>
<li>Understand terms and concepts related to networking: protocol, IP, port, URL, socket, and datagram.</li>
<li>Get familiar with the client-server programming model.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>Write programs that communicate with other programs on the network, using TCP or UDP.</li>
<li>Get acquainted with RMI technology.</li>
</ul>
</div>
</div>
</div>

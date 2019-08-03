<h3>STOMP Web-Socket chat.</h3>

[![Build Status](https://travis-ci.com/vsevolodkolobov/stompchat.svg?branch=master)](https://travis-ci.com/vsevolodkolobov/stompchat)

STOMP (Streaming Text Oriented Messaging Protocol): a communication protocol, a branch of the  WebSocket. When the  client and the  server contact each other by this protocol, they will send each other text message data. The relationship between  STOMP and  WebSocket is also similar to the one between HTTP and  TCP.<br>
In addition, the  STOMP also provides a specific way to solve the following functions:  

<table align="left">
 
<tr align="justify"><th>Function</th><th>Description</th></tr>
<tr align="justify"><th>Connect</th><th>	Provide ways so that the client and the server can connect to each other.</th></tr>
<tr align="justify"><th>Subscribe	</th><th>Provide ways so that the  client  subscribes receipt of messages of a topic.</th></tr>
<tr align="justify"><th>Unsubscribe	</th><th>Provide ways so that the  client unsubscribes the receipt of messages of a topic.</th></tr>
<tr align="justify"><th>Send	</th><th>How the client sends messages to the server.</th></tr>
<tr align="justify"><th>Message	</th><th>How to send a message sent from the server to the client.</th></tr>
<tr align="justify"><th>Transaction management</th><th>	Transaction management during data transfer (BEGIN, COMMIT, ROLLBACK,...)</th></tr>

</table>

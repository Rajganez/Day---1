<h1 align="center">HTTP 1.1 Vs HTTP 2 difference</h1>
<p align="center">

<h2 align="left">The First usable HTTP called HTTP/1.1 was created in 1997. This version is still use on web </h2>
<h2 align="left">The New version of HTTP called HTTP/2 was created in 2015. Which is faster and more efficient than older version. In one way it priorities content during the loading process. </h2>
<h2 align="center"><b>Below differences for HTTP/2 and HTTP/1.1 </b></h2>

<table><tr><th>HTTP/2</th> <th>HTTP/1.1</th></tr>
<tr><td> <b>Prioritization: </b>Developer has hands on detail control over prioritization  <br><b>Multiplexing:</b>It uses single TCP connection to send multiple streams of data, It does this by splitting data into binary code messages and numbering these messages so client knows which stream each binary   message belong to<br><b>Server Push: </b>It enables multiple concurrent responses to a client's intial GET request a server can send a resource to a client along with the requested HTML page, providing the resourse before the client asks<br><b>Header compressios:</b>It uses more advanced compression method called HPACK. HPACK uses three methods of compressions <i>Static dictionary, Dynamic dictionary, Huffman Encoding</i>  </td>
<td> <b>Prioritization: </b>That was not possible in HTTP/1.1 <br><b>Multiplexing:</b>It load resources one after the other<br><b>Server push:</b>It uses Server inlining which decreases the connection speed, Major drawback is client cannot separate the resource and document,if the developer knows in advance which additional resources the client machine will need to render the page, they can use a technique called resource inlining<br><b>Header compressions:</b>Small files load quick to speed up the performance to compress HTTP messages to make them smaller </td></tr>
</table>

<h2 align="center"><b> HTTP/3 is the next proposed version of the HTTP protocol. It does not have wide adoption on web, it runs over QUIC instead of TCP </b></h2>

</p>




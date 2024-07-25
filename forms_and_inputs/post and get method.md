Basic:
    HTTP protocal faciliates communication between client and server.
    Two types of data transmission methods :POST and GET.

Post:
    Submits data to be processed to a specified resources.
    send name/value pairs in the HTTP message body.

ex:
POST send.php HTTP/1.1
Host: youaccel.com
fname=john&lname=smith

Get:
   + request data from a specified resource.
   + Name/Value pairs are sent in the URL String.

Ex: send.php?fname=john&lname=smith

Get Requests:
   + can be cached.
   + Remain in browser history.
   + Should only be used to retrieve data.
   + Have length Restrictions.
   + Should not be used for sensitive data.
   + Can be bookmarked.

Post method:
   + No restriction on data length.
   + Cannot be bookmarked.
   + Do not remain in browser history.
   + Requests are never cached.
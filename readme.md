This branch is made while we rewrote the socket_to_serial branch

Reasons are the need for new hardware generations of raspberry pi and compatibility reasosns for PI and Python in future.
Therefore Lifeline was replaced from socket_to_serial to hd2000ServiceServer which controls not the transfer of the
Webserver Counter and stops therapy when service server gets no counter while disconnected.


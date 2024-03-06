https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works
https://en.wikipedia.org/wiki/Nginx
https://www.digitalocean.com/community/tutorials/how-to-set-up-nginx-server-blocks-virtual-hosts-on-ubuntu-16-04
Learn what Child process is ==> 

What is a Child Process?
Although it may sound like something out of a parenting handbook or a psychological journal, the term child process actually has nothing to do with human development. If you run a Unix or Linux dedicated server, you have likely encountered child processes without even knowing it. Therefore, it is good to know what child processes are and how they work.

A child process is a process created by another process. The creator process is properly called the “parent process”. The benefit of a child process is that it can start or stop at will without affecting the parent process. The child process is, however, is typically dependent on the parent process. If the parent process dies, the child process becomes an orphan process.

In normal server operations, the kernel may initiate child processes, and other programs, such as Apache, may have them as well. Apache creates child processes (or children, if you prefer) whenever the number of requests (web page accesses from users) exceeds the maximum allowed number of requests. When the maximum number of child process requests is exceeded, another child process spawns.

To view all running processes along with their child processes in a “tree” format, use the following command:

$ ps axf
For more information about child processes, see this documentation.


https://landingi.com/help/domains-vs-subdomains/
https://www.tutorialspoint.com/http/http_methods.htm
https://moz.com/learn/seo/redirection
https://en.wikipedia.org/wiki/HTTP_404
https://www.cyberciti.biz/faq/ubuntu-linux-gnome-system-log-viewer/
https://datatracker.ietf.org/doc/html/rfc7231
https://datatracker.ietf.org/doc/html/rfc7540

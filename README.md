Task: to develop dynamic routing for Symfony3 
=====

1. We cannot use Symfony CMF. I found it works for Symfony2 only.

2. Custom routing
https://github.com/mixtline/test-task-1

3. Catch kernel.request event
https://github.com/mixtline/test-task-2

4. According to Symfony3 documentation we can use route configs in php. 
It means we can get current path in our /app/config/routing.php, split it (the same way as we did for 2 and 3)
and get correct route (or exception if the route is wrong).

5. To develop a script that will find all bundles and will generate routing.yml for all found controllers.
 The only negative face - we will need to run the script after deploy or after each adding/removing action in the controllers.

# twig-json-decode

Twig Extension, Symfony implementation for the json_decode function.

1. Create the Twig\Extension directories within your bundle (in this case we are using the default AppBundle).
2. Create JsonDecode.php class
3. Tell the container to add the service by adding the new class to your services.yml
4. Use the new filter in any twig file!

**example.twig.html**

    {{ data|json_decode }}

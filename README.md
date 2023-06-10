# Index COM

## Descriptcion:
Una website basica para dopeldev.com. Lo hare con Flask con Guvicorn y Nginx como reverse proxy, ademas de certbot para los certificados SSL.

## Technical details:
- **BackEnd:** Usare **Flask** para crear la site porque es un **framework minimalista** 
y en este caso no necesito muchas features.
Usare Guvicorn como WSGI, ya que no necesito ninguna asynchronous feature, Guvicorn es un
**Web Server Gateway Interface**.
Usare **Nginx** como **Reverse Proxy**, pues se como usarlo basicamente.

- **FrontEnd:** Usare el framework **Bulma**, porque no requiere dependecias en javascript. 


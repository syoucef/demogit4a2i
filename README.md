

La commande à utiliser pour cloner un dépôt en local avec Git
``git clone``


1. Introduction à GIT
2. Services Web SOAP
3. Services Web Rest
4. Injection des dépendances et inversion de contrôle 


* item 1
* item 2
* item 3
* item 4


[lien du dépôt du cours sur GIT](https://github.com/syoucef/demogit4a2i)

L'objectif est d'introduire les verbes pull et push .....
Je suis entrain d'apporte des modifications en local ...

ici un exemple du code Java ....

```java
package org.sid.demoweb;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;
@SpringBootApplication
@RestController
public class DemoWebApplication {
    public static void main(String[] args) {
        SpringApplication.run(DemoWebApplication.class, args);
    }
    @GetMapping("/test")
    public String test(){
        return "Bonjour Inès et Augustin, de Spring !";
    }
}

```

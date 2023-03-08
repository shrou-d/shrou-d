```java
import galaxy.earth.shroud;
public class Shroud{

    static void languages(){
        String languages = {"Java","TypeScript","C++","Python"};
        for(byte control = 0; control <= languages.length; control++){
            System.out.println("I code in :" + languages[0]);
        }
    }
    static void frameworks(){
        String frameworks = {"Next.JS","Spring Boot","Arduino","Express.JS","PyTorch","Keras","TensorFlow"};
        for(byte control = 0; control <= frameworks.length; control++){
            System.out.println("I write in " + frameworks[0] + " framework");
        }
    }
    static void about(){
        String goals = {"Open Source"};
        for(byte control = 0; control <= goals.length; control++){
            System.out.println("Code to contribute to " + goals[0] + "Software & Communties");
        }
    }
    static void main(String args[]){
       Shroud shroud = new Shroud();
       shroud.languages();
       shroud.frameworks();
       shroud.about();
    }
}
```

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
<script async
  src="https://js.stripe.com/v3/buy-button.js">
</script>

<stripe-buy-button
  buy-button-id="buy_btn_1MjQxDSHKhnGM9JoOY2b2uGd"
  publishable-key="pk_live_51MhCxQSHKhnGM9JoyDY3R7mZduqv4ExT35RKceIBDOCQDGPhGfysJacmejGT6MT5pixtevKwFR8fJBXNmGfcdp7R00OPAidziC"
>
</stripe-buy-button>

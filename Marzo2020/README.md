# Kotlin Meetup Marzo 2020

![Kotlin Meetup Banner](resources/banner.png)

## Charlas 

### Eddú Meléndez 
_Software Engineer en Nubank_

[**Consumer Driven Contract Testing con Spring Cloud Contract**](resources/slide)

En plena era de microservicios, escribir pruebas puede sonar sencillo ya que nos hacemos 
responsables de solo un dominio. Pero, en el mundo real, las pruebas de los microservicios 
pueden ser duras. En esta sesión, veremos cómo CDC Testing nos ayuda a mantener nuestros 
servicios trabajando juntos. Estaremos explorando el proyecto Spring Cloud Contract 
haciendo uso de Kotlin DSL.

## Kotlin Resources

[Exploring Kotlin/Native by Big Nerd Ranch](https://www.bignerdranch.com/blog/exploring-kotlin-native-part-1/)

![[Exploring Kotlin/Native by Big Nerd Ranch](https://www.bignerdranch.com/blog/exploring-kotlin-native-part-1/)](resources/bignerdranch.png)



[Authorization for a Kotlin Spring backend, using JSON Web Tokens](https://itnext.io/authorization-for-a-kotlin-spring-backend-using-json-web-tokens-9f3c7b0d1ee7)

[![Authorization for a Kotlin Spring backend, using JSON Web Tokens](resources/auth.png)](https://itnext.io/authorization-for-a-kotlin-spring-backend-using-json-web-tokens-9f3c7b0d1ee7)



[Kotlin Vocabulary - Android Developers Youtube](http://youtube.com/watch?v=OyIRuxjBORY)

[![Kotlin Vocabulary - Android Developers Youtube](resources/ktvocabularyYT.png)](http://youtube.com/watch?v=OyIRuxjBORY)




##

Kotlin 1.3.70 released!!!

![Kotlin 1.3.70](resources/k137release.png)
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">We’ve just released Kotlin 1.3.70! Learn all about the new experimental functionality in the standard library and other improvements in our latest blog post <a href="https://t.co/jlyThHFgmb">https://t.co/jlyThHFgmb</a> <a href="https://t.co/md7Eqa5rLv">pic.twitter.com/md7Eqa5rLv</a></p>&mdash; Kotlin (@kotlin) <a href="https://twitter.com/kotlin/status/1234917943970009090?ref_src=twsrc%5Etfw">March 3, 2020</a></blockquote>


Kotlin 1.4.M1 released!!!

![https://blog.jetbrains.com/kotlin/2020/03/kotlin-1-4-m1-released/](resources/kt14preview.png)

#### SAM conversion for Kotlin functions and interfaces

SAM conversion allows you to pass a lambda when an interface with one “single abstract method” is expected. Before, you could only apply SAM conversion when working with Java methods and Java interfaces from Kotlin, and now you can use it with Kotlin functions and interfaces as well.

```kotlin
fun interface Action {
    fun run()
}

fun runAction(a: Action) = a.run()

fun main() {
    runAction {
        println("Hello, Kotlin 1.4!")
    }
}
```

![How to 1.4](resources/iwantitnow.gif)

[How to 1.4](https://kotlinlang.org/eap/install-eap-plugin.html?_ga=2.195523498.741204059.1585349604-1181474551.1546729213)
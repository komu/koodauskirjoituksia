# komun koodauskirjoituksia

Lähdekoodi osoitteesta [https://komun-koodauskirjoituksia.evident.fi/](https://komun-koodauskirjoituksia.evident.fi/)
löytyville komun koodauskirjoituksille.

## Buildaus

Teksti on kirjoitettu [Asciidoctorilla](http://asciidoctor.org/) ja siitä voidaan buildata sekä PDF- että HTML-versiot
sanomalla `./gradlew clean build`. Tekstiä muokattaessa on hyödyllistä käyttää Gradlen _continuous build_ -moodia ja 
sanoa `./gradlew -t asciidoctor`.

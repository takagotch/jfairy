### jfairy
---
https://github.com/Codearte/jfairy

```java
Fairy fairy = Fairy.create();
Person person = fairy.person();

System.out.println(person.fullName());

System.out.println(person.email());

System.out.println(person.telephoneNumber());

Person adultMale = fairy.person(male(), minAge(21));
System.out.println(adultMale.isMale());

System.out.println(adultMale.dateOfBirth());


Fairy fairy = Fairy.create();
Company company = fairy.company();
System.out.println(company.name());

System.out.println(company.url());

Person salesman = fairy.person(withCompany(company));
System.out.println(saleman.fullName());
System.out.println(salesman.companyEmail());

Fairy enFairy = Fairy.create();
Fairy plFairy = Fairy.create(Locale.forLanguageTag("pl"));
```

```sh
./gradlew build
./gradlew publishToMavenLocal
```

```
```



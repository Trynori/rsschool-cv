# **[rsschool-cv]**(https://Trynori.github.io/rsschool-cv/cv)


# **Kharitonov Alexander**
## **Junior fullstack Developer**
### **Contact information:**
* phone: +375 (29) 545-53-70
* Email: sasha.xaritonov.1995@mail.ru
* Discord: Aternass#2297
### **About Myself:**
3rd year student of Belarusian State University transport. I study software development technologies tension, java programming language, algorithms and patterns design. I consider it my priority develop client-server applications.
### **Skills:**
* HTML5, CSS3
* Java 11(Spring web, Lambok, spring security, Hibernate, Spring boot)
* Maven/Gradle
* PostgresSQL, redis
* Git, GitHub, BitBucket
### **Code example:**
```
 public List<ParameterModel> analysisIndicators(List<ParameterModel> firstParameters, List<ParameterModel> secondParameters) {
        List<ParameterModel> parameterList = firstParameters.stream().map(parameter -> {
            ParameterModel comparedParameter = secondParameters.stream()
                    .filter(p -> p.getId() == parameter.getId())
                    .findFirst()
                    .get();
            parameter.setAnalysis(parameter.getValue() > comparedParameter.getValue());
            return parameter;
        }).collect(Collectors.toList());

        return parameterList;
    }
```
### **Languages:**
* English - Elementary
* Russian - Native
* Belarusian - Native

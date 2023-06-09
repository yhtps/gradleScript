# gradleScript

a useful set of gradle scripts

you can apply these scripts on your "build.gradle"

```gradle
apply from:"/writeChangelog.gradle"
apply from:"/springJpaCodegen.gradle"

```

[springJpaCodegen.gradle](https://github.com/yhtps/gradleScript/blob/main/scirpts/springJpaCodegen.gradle)

> add task for generating spring jpa related mvc code

[writeChangelog.gradle](https://github.com/yhtps/gradleScript/blob/main/scirpts/writeChangelog.gradle)

> add task for updating your changelog based on your commit details

[changelogTemplate](https://github.com/yhtps/gradleScript/blob/main/scirpts/writeChangelog.gradle#L22-L34)

![changelog example](https://github.com/yhtps/gradleScript/blob/main/scirpts/img/changelog%20example.png)

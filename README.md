# gradleScript

a useful set of gradle scripts

![gif](https://github.com/yhtps/gradleScript/blob/main/scirpts/img/generateQueryDslRepo.gif)

you can apply these scripts on your "build.gradle"

```gradle
apply from:"/writeChangelog.gradle"
apply from:"/springJpaCodegen.gradle"

```

![tasks](https://github.com/yhtps/gradleScript/blob/main/scirpts/img/tasks.png)

[springJpaCodegen.gradle](https://github.com/yhtps/gradleScript/blob/main/scirpts/springJpaCodegen.gradle)

> add task for generating spring jpa related mvc code

**this will generate code based on the entity".**

[writeChangelog.gradle](https://github.com/yhtps/gradleScript/blob/main/scirpts/writeChangelog.gradle)

> add task for updating your changelog based on your commit details

**this will overwrite “CHANGELOG.md” if it exists or the changelog template does not match the existing.**

[changelogTemplate](https://github.com/yhtps/gradleScript/blob/main/scirpts/writeChangelog.gradle#L22-L34)

![changelog example](https://github.com/yhtps/gradleScript/blob/main/scirpts/img/changelog%20example.png)

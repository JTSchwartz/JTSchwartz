![Profile Banner](https://github.com/JTSchwartz/JTSchwartz/blob/master/Banner.png)
<br/><br/>
[![Website](https://img.shields.io/badge/%20-jtschwartz.com-%23145762?style=for-the-badge)](https://jtschwartz.com)
[![Gmail Badge](https://img.shields.io/badge/-jacob@jtschwartz.com-c14438?style=for-the-badge&logo=Gmail&logoColor=white&link=mailto:jacob@jtschwartz.com)](mailto:jacob@jtschwartz.com)
[![Twitter Badge](https://img.shields.io/badge/-@DevSchwartz-1ca0f1?style=for-the-badge&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/DevSchwartz)](https://twitter.com/DevSchwartz)
[![Linkedin Badge](https://img.shields.io/badge/-Jacob_Schwartz-blue?style=for-the-badge&logo=LinkedIn&logoColor=white&link=https://www.linkedin.com/in/jacob-t-schwartz/)](https://www.linkedin.com/in/jacob-t-schwartz/) 


B.S. in Computer Science from the University of Dayton<br/>
Full Stack Software Developer at Ford Motor Company<br/>

```kotlin
package com.github.jtschwartz.profile

class About:Me {
    companion object {
        val almaMater = "University of Dayton"
        var company = "Ford Motor Company"
        var position = "Software Developer"
    }

    fun techStack() {
        val languages = arrayOf(
            "Kotlin",
            "Java",
            "JavaScript",
            "Python",
            "Go"
        )

        return languages + platforms()
    }

    private fun platforms() {
        return arrayOf(
            "Android",
            "Linux",
            "Windows",
            "Web"
        )
    }
}
```

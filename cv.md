
---
# Olga Melnichuk
---
### Contacts
> Location: Krakow, Poland
> E-mail: melnichuk.olga7@gmail.com
> GitHub: bad-tea-bag
> Linkedin: olga-melnichuk
---
### About me
I'm Olga Melnichuk, a Junior Frontend Developer. Currently, I'm working as an Automation QA Engineer(Java), but I'd like to try something new so I decided to start JavaScript/Front-end pre-school course at RS School and learn front-end.
---
### Skills
- HTML, CSS, JS (basic knowledges)
- Java, TestNG, Selenium
- Git, GitHub
- VS Code, IntelliJ IDEA
- SDLC and methodologies (agile, scrum, kanban)
- Jira, Bug Reporting
- Adobe After Effect
---
### Foreign languages
**English** - Intermediate 
---
### Code example
```
function censor() {
    const array = [];
    return (str1, str2 = '') => {
        if (str2) {
            array.push([str1, str2]);
        } else {
            for (var prop of array) {
                str1 = str1.replace(new RegExp(prop[0]), prop[1]);
            }
            return str1;
        }
    }
}
```
<h2 align="center">About Me </h2>

```javascript
class Temirlan {
    constructor(name) {
        this.name = name;
    }

    introduction() {
        return `Hello, my name is ${this.name}. I'm a full-stack developer!`;
    }
}

class Attributes extends Temirlan {
    get contact() {
        const instagram = "instagram.com/temirlannz";
        const telegram = "t.me/temirlannz";
        const email = "t.zhanibek@bk.ru";
        
        return [instagram, telegram, email];
    }

    get life() {
        const langs = ['Kazakh', 'English', 'Russian'];
        const age = 21;
        
        return [langs, age];
    }

    get coding() {
        const langs = {
            'good in': ['javascript'],
            'intermediate': ['python'],
        };
        const specialities = ['front-end', 'fullstack'];
        const environment = ['webstorm'];

        return [langs, specialities, environment];
    }
}

const temirlan = new Attributes("Temirlan");
```

<h2 align="center">Skills</h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=js,html,css,ts,python,react,nextjs,nodejs,express,postgres,prisma,tailwind,ps,figma" />
  </a>
</p>

<p align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=temirlannz&show_icons=true&theme=dark&locale=en&layout=compact" alt="temirlannz" />
</p>

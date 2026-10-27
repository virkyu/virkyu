![Wzium](https://img.shields.io/badge/student-true-green) ![frauds.pro](https://img.shields.io/badge/owner%20of-frauds.pro-blue) ![Discord](https://img.shields.io/badge/discord-virkyu-%237289DA?logo=discord&logoColor=white)


### 👋 Hello

```javascript
class Virkyu {
    nick: string;
    age: string; // I wanna be mysterious
    hobby: string[];
    languages: string[];
    lazy: boolean;

    constructor() {
        this.nick = "Virkyu";
        this.age = "1?";
        this.hobby = ["coding", "design", "raging at isaac :("];
        this.languages = ["js", "ts", "php/2", "py/3", "java/3", "C#/2", "C++/3"];

        this.lazy = true;
    }

    greet(): string {
        return this.lazy ? "o/" : "HIII, how are you doing? :))";
    }

    info(): string {
        return "Feel free to let me know about any bugs, im just a human";
    }
}

const nerd = new Virkyu();
console.log(nerd.greet());
```

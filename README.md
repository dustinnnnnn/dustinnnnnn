### <p align="center">👋</p>

<hr>

```javascript
import { Dustin } from "https://dustin.gg/me/dustin.ts";

(async () => {
    try {
        const me = await Dustin.getPresentState();

        if (me.isAwake()) {
            if (me.isTired()) {
                await me.sleep(3.6e7);
            } else {
                !me.isLazy() && await me.work();
            }
        } else {
            return "Sleeping, try again later.";
        }
    } catch (err) {
        switch (err.name) {
            default:
                me.checkSelf();
                break;
            case "InternalError":
                return "wasted";
        }
    }
})();
```

<hr>
<p align="center">
<!--<img src="https://gpvc.arturio.dev/dustinsbustin"/>
<br/>-->
<img style="height: 20px" alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/><img style="height: 20px" alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/><img style="height: 20px" alt="CSS3" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/><img style="height: 20px" alt="NodeJS" src="https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white"/><img style="height: 20px" alt="MySQL" src="https://img.shields.io/badge/mysql-%2300f.svg?&style=for-the-badge&logo=mysql&logoColor=white"/>
<br/>
<img style="height: 20px" alt="Visual Studio Code" src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?&style=for-the-badge&logo=visual-studio-code&logoColor=white"/><img style="height: 20px" alt="Figma" src="https://img.shields.io/badge/figma%20-%23F24E1E.svg?&style=for-the-badge&logo=figma&logoColor=white"/><img style="height: 20px" alt="Bitcoin" src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white" />
<br/>
<img style="height: 20px" alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" /><img style="height: 20px" alt="Windows 10" src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
</p>

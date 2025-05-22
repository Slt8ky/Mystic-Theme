# Mystic Theme V1
A theme that has custom background feature.

![repository-open-graph-template](https://github.com/user-attachments/assets/424d8972-9ec6-4748-a876-b50ac2949550)
![image](https://github.com/user-attachments/assets/c8f93f61-81b9-49b8-a94e-1434124be0b9)
![image](https://github.com/user-attachments/assets/459aecb5-54f4-48ed-9def-b99a030b354b)
![image](https://github.com/user-attachments/assets/9a6c2577-1f18-4107-9e3c-0c01861c2c53)
![image](https://github.com/user-attachments/assets/048f6421-1de6-4438-8f53-09d22d29b3fa)
![image](https://github.com/user-attachments/assets/72c514fb-fa23-45c3-82ff-4a4e1d486305)

## How to install
> [!NOTE]
> You need to download third-party Discord application such as Vencord, BetterDiscord to apply the theme.

### 1. Download thrid-party Discord
**Vencord**
> [https://vencord.dev/download/](https://vencord.dev/download/)

or

**BetterDiscord**
> [https://vencord.dev/download/](https://betterdiscord.app/)

### 2. Download theme.css and drag to file location press Win + R
**Vencord**
> %appdata%/Vencord/themes

**BetterDiscord**
> %appdata%/BetterDiscord/themes

### 3. Apply theme in Discord
Go to Discord > Settings > theme > enable theme.css

## Additonal & Theme Customization:
> Comment and uncomment base on what you need in Present sections, there are already provided few wallpaper and filter, if you wanna use custom wallpaper comment the current present and uncomment the custom present and configure the parmater.

```css
:root {
    --background-image: "";
	--loading-image: url(https://i.pinimg.com/1200x/07/02/06/0702067fc6e3207de2aa6203144befd5.jpg);    
	--main: rgb(19, 12, 18);
    --border: rgb(91, 91, 91);
    --heading: rgba(193, 176, 178, 0.03);
    --text: rgba(47, 35, 37, 0.112);
    --primary: rgb(255, 47, 82);
    --secondary: rgb(144, 102, 165);
    --loadintime: 4s;

    .appAsidePanelWrapper_a3002d {
        position: relative;

        /* Present 1 */
        /* &::before {
            background: url(https://i.ibb.co/JRDVL3mT/PHONK-MIX-FOR-NIGHT-DRIVE-BEST-LXST-CXNTURY-TYPE-3-HOUR-CAR-MUSIC-2025-1-59-3-screenshot.png) center / 40% !important;
            filter: brightness(60%) contrast(65%);
        }

        &::after {
            mask: radial-gradient(25% 25%, transparent, red) !important;
            backdrop-filter: sepia(20%) brightness(50%);
        } */

        /* Present 2 */
        /* &::before {
            background: url(https://i.ibb.co/39H6vh3n/b1.jpg) center / cover !important;
            filter: brightness(66%) contrast(130%);
        }

        &::after {
            mask: radial-gradient(25% 25%, transparent, red) !important;
            backdrop-filter: sepia(20%) brightness(30%);
        } */

        /* Present 3 */
        &::before {
            background: url(https://i.ibb.co/5WYkvvFQ/b2.png) center / cover !important;
            filter: brightness(190%) contrast(120%); 
        }

        &::after {
            mask: radial-gradient(25% 25%, transparent, red) !important;
            backdrop-filter: sepia(20%) brightness(50%);
        }

        /* Present 4 */
        /* &::before {
            background: url(https://i.ibb.co/Z1vkXjvV/b3.png) center / cover !important;
            filter: brightness(120%) contrast(100%);
        }

        &::after {
            mask: radial-gradient(40% 55%, transparent, red) !important;
            backdrop-filter: sepia(20%) brightness(50%) blur(3px);
        } */

        /* Custom Present */
        /* &::before {
            background: url("") center / cover !important;
            filter: unset;
        }

        &::after {
            mask: radial-gradient(40% 55%, transparent, red) !important;
            backdrop-filter: unset;
        } */
    }
}
```

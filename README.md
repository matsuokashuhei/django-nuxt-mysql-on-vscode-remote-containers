Django, Nuxt.js, and MySQL development environment using Visual Studio Code Remote - Containers
==

# How to Use

## Open editor with development environment

### Django app

1. Open your VS Code
2. `F1` > `Remote Containers: Open Folder in Container...` and select `django` folder
3. Open new terminal and run `django-admin startproject mysite .`.
4. After `django-admin startproject mysite`, run `python manage.py runserver 0:8000` on terminal.

### Nuxt.js app

1. Open new window
2. `F1` > `Remote Containers: Open Folder in Container...` and select `nuxt` folder
:construction:
3. Open new terminal in VS Code and run `npx create-nuxt-app .`.
4. After `npx create-nuxt-app .`, run `npm run dev` on terminal.

:construction: If you want to open both environments, open two windows in your VS Code.

# Built-in Extensions in Development environment

## Django

- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

## Nuxt.js

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=visualstudioexptteam.vscodeintellicode)
- [Vue Peek](https://marketplace.visualstudio.com/items?itemName=dariofuzinato.vue-peek)


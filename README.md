# Уличный артист

## Описание проекта

Проект представляет собой платформу, предоставляющую артистам возможность беслпатно выступить на площадках в Москве и МО. Основные функциональности включают в себя: выбор площадки разных типов в парках и городе с возможностью фильтрации и картой, выбор часов для бронирования, форма для бронирования и заполнение данных о коллективе или артисте, а также страница для полиции с верификацией статуса артиста. 

## Назначение проекта

Этот проект был разработан с целью предоставления инструмента для выступлений в городе и парках Москвы.

## Галерея

![Изображение 1](https://github.com/BrandonWF1/streetmusic/blob/main/screen%201.png)
![Изображение 2](https://github.com/BrandonWF1/streetmusic/blob/main/screen2.png)
![Изображение 3](https://github.com/BrandonWF1/streetmusic/blob/main/screen%203.png)
![Изображение 4](https://github.com/BrandonWF1/streetmusic/blob/main/screen%204.png)
![Изображение 5](https://github.com/BrandonWF1/streetmusic/blob/main/screen5.png)
![Изображение 6](https://github.com/BrandonWF1/streetmusic/blob/main/screen%206.png)

## Моя роль в проекте

in progress

## Технологии, используемые в проекте

  ![NextJS](https://img.shields.io/badge/-NextJS-black?style=for-the-badge&logo=next.js)
  ![Typescript](https://img.shields.io/badge/-Typescript-white?style=for-the-badge&logo=typescript)
  ![SCSS](https://img.shields.io/badge/-SCSS-pink?style=for-the-badge&logo=sass)
  ![Redux Toolkit](https://img.shields.io/badge/-Redux_Toolkit-purple?style=for-the-badge&logo=redux)
  
## Принципы и инструменты разработки
- Код-стиль и форматирование: Prettier
- Система контроля версий: Git + GitLab
- Прочие инструменты: maki (Собственная devOps разработка), Cypress, Sonar
- Линтер: ESLint
  <details>
  <summary>Конфиг linter`а</summary>
  
  ```javascript
  {
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaVersion": 2018,
    "ecmaFeatures": {
      "jsx": true
    },
    "useJSXTextNode": true
  },
  "env": {
    "browser": true,
    "node": true,
    "commonjs": true,
    "jest": true
  },
  "extends": [
    "plugin:@typescript-eslint/recommended",
    "react-app",
    "airbnb",
    "prettier"
  ],
  "plugins": [
    "@typescript-eslint",
    "react-hooks",
    "jsx-a11y"
  ],
  "rules": {
    "@typescript-eslint/no-var-requires": 0,
    "global-require": 0,
    "semi": 2,
    "react/jsx-key": 2,
    "no-use-before-define": 0,
    "react/require-default-props": 0,
    "@typescript-eslint/ban-ts-ignore": 0,
    "no-shadow": 0,
    "arrow-body-style": "warn",
    "@typescript-eslint/ban-types": 0,
    "@typescript-eslint/ban-ts-comment": 0,
    "@typescript-eslint/no-unused-vars": 1,
    "@typescript-eslint/no-empty-function": 1,
    "@typescript-eslint/no-use-before-define": 2,
    "@typescript-eslint/no-explicit-any": [
      2,
      {
        "ignoreRestArgs": false
      }
    ],
    "@typescript-eslint/interface-name-prefix": 0,
    "@typescript-eslint/explicit-member-accessibility": 0,
    "import/no-extraneous-dependencies": [
      2,
      {
        "devDependencies": true
      }
    ],
    "import/prefer-default-export": 0,
    "spaced-comment": [
      "error",
      "always",
      {
        "markers": [
          "/"
        ]
      }
    ],
    "react/jsx-filename-extension": [
      1,
      {
        "extensions": [
          ".js",
          ".jsx",
          ".tsx"
        ]
      }
    ],
    "react-hooks/rules-of-hooks": "error",
    "react-hooks/exhaustive-deps": "warn",
    "@typescript-eslint/explicit-function-return-type": 0,
    "@typescript-eslint/prefer-function-type": 2,
    "no-param-reassign": [
      "error",
      {
        "props": true,
        "ignorePropertyModificationsFor": [
          "state"
        ]
      }
    ],
    "jsx-a11y/label-has-associated-control": [
      2,
      {
        "labelComponents": [
          "CustomInputLabel"
        ],
        "labelAttributes": [
          "label"
        ],
        "controlComponents": [
          "CustomInput"
        ],
        "depth": 3
      }
    ],
    "jsx-a11y/label-has-for": 0,
    "react/jsx-props-no-spreading": 0,
    "import/extensions": [
      "error",
      "ignorePackages",
      {
        "js": "never",
        "jsx": "never",
        "ts": "never",
        "tsx": "never"
      }
    ],
    "react/destructuring-assignment": 1
  },
  "overrides": [
    {
      "files": [
        "*.js"
      ],
      "rules": {
        "@typescript-eslint/no-var-requires": "off"
      }
    },
    {
      "files": [
        "style.ts"
      ],
      "rules": {
        "import/no-unresolved": 0
      }
    },
    {
      "files": [
        "*.ts",
        "*.tsx"
      ],
      "rules": {
        "no-undef": 0
      }
    }
  ],
  "settings": {
    "import/resolver": {
      "node": {
        "extensions": [
          ".js",
          ".jsx",
          ".ts",
          ".tsx"
        ]
      }
    }
  }
  }
</details>

## Команда
- Общее количество человек: 11
- Роли в команде:
  - Front-End: 1
  - Back-end: 2
  - Дизайнеров: 2
  - Тестировщиков: 2
  - Lead: 1
  - Аналитиков: 1
  - Product & Project Managment: 2
    
# Основные достижения и результаты


## Особые вызовы и преодоленные препятствия

- **exp**

## Ссылки

- **Проект**: mos.ru/arenda.
- **Код проекта**: Код находится под защитой соглашения о неразглашении (NDA), из-за чего, к сожалению, не может быть предоставлен для общего доступа или просмотра.

# SN-BLOG

## Purpose of this project
- This project is to learn how to develop site in JAMSTACK way with the free of costs.
- Another purpose is to remember how to build a react site.
- Ref-site: this site is built by following site instruction
    - [git](https://github.com/tsuchinoko0402/old_website/blob/main/README.md?plain=1)
    - [Qiita](https://qiita.com/tsuchinoko0402/items/e47b2e05c47773130b11)

## Tech stack
- TypeScript
- Gatsby
- microCMS
- Firebase

## Tested template
### sn-blog
### test

## Actication Steps
1. Register microCMS, and get API and service keyキーとサービス ID
- Set the env-variables
    - `MICROCMS_API_KEY`: The API key value of Micro CMS
    - `MICROCMS_SERVICE_ID`: The service ID for microCMS
    - `GOOGLE_ANALYTICS_TRACKING_ID`: Tracking id for Google Analytics

2. Deploy env server
```shell
$ yarn develop
```

3. build
```shell
$ yarn build
```

4. Acctivation process of the working env-server
- Create an account on the Firebase
- Make the project
- Change the setting of `.firebaserc` 

5. Deploy command
```shell
$ yarn deploy
```

> This is just a firebase deployment
> You need to first test your local env 
```shell
$ gatsby develop
```
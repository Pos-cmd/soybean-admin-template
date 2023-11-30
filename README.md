<div align="center">
	<img src="./public/favicon.svg" style="width: 160px;"/>
	<h1>Soybean Admin</h1>
</div>

[![license](https://img.shields.io/badge/license-MIT-green.svg)](./LICENSE) ![](https://img.shields.io/github/stars/honghuangdc/soybean-admin) ![](https://img.shields.io/github/forks/honghuangdc/soybean-admin)

## Attention : SoybeanAdmin est en cours de refonte, la toute nouvelle version 1.0 devrait être publiée courant décembre

Soybean Admin v1.0 :

- [x] Utilisation d'un projet de gestion monorepo basé sur pnpm
- [x] Extraction directe de la bibliothèque d'outils tierce soybeanjs dans le projet (à l'exception d'ElegantRouter), ne la considérant plus comme une dépendance
- [x] Adoption du tout nouveau plugin de routage ElegantRouter
- [x] Utilisation du mock distant basé sur ApiFox en remplacement du mock local
- [x] Guide de migration du plugin de routage actuel vers le nouveau plugin de routage
- [x] Respect des normes de code SoybeanJS
- [ ] La branche principale du projet conserve la partie centrale du système, les pages d'exemple et les plugins non essentiels sont déplacés vers la branche example
- [ ] Documentation complète pour la version 1.0

  Code source 1.0 : [v1.0-beta](https://github.com/honghuangdc/soybean-admin/tree/v1.0-beta)

> Introduction simultanée des versions AntDesignVue et ElementPlus nécessitant une licence commerciale


## Introduction

[Soybean Admin](https://github.com/honghuangdc/soybean-admin) est un modèle d'administration clair et élégant pour les applications de gestion basées sur Vue3, Vite3, TypeScript, NaiveUI, Pinia et UnoCSS. Il utilise les technologies frontales les plus récentes, offre une configuration de thème riche, respecte des normes de code élevées, dispose d'un système de routage basé sur les fichiers et d'autorisations dynamiques basées sur Mock, offrant une solution frontale clé en main pour les applications de gestion, ainsi qu'une référence utile pour l'apprentissage.

## Caractéristiques

- **Dernières technologies frontales** : Utilisation des technologies frontales telles que Vue3/Vite, avec un gestionnaire de paquets npm efficace, pnpm.
- **TypeScript** : Langage de programmation pour des applications JavaScript de niveau professionnel.
- **Thème** : Possibilité de configurer des thèmes riches, un mode sombre et des couleurs de thème dynamiques basées sur UnoCss, un framework CSS atomique.
- **Normes de code** : Nombreux plugins de normes et normes de code très élevées.
- **Système de routage basé sur les fichiers** : Génère automatiquement des déclarations de routage, des imports de routage et des modules de routage en fonction des fichiers de page.
- **Routes d'autorisation** : Propose deux modes de routage : statique côté frontend et dynamique côté backend, grâce à des routes dynamiques basées sur Mock pour une mise en œuvre rapide des routes dynamiques côté backend.
- **Fonctions de requête** : Encapsulation complète de fonctions de requête basées sur Axios, offrant à la fois des fonctions de requête Promises et des hooks, avec un adaptateur pour la transformation des données de résultat de requête.

## Bibliothèque d'outils SoybeanJS

- [@soybeanjs/cli](https://github.com/soybeanjs/cli) : Outil en ligne de commande SoybeanJS incluant des commandes pratiques telles que la publication, le git et la gestion des dépendances.
- [@soybeanjs/changelog](https://github.com/soybeanjs/changelog) : Génère un changelog en fonction des tags git et des commits [exemple](./CHANGELOG.md)
- [eslint-config-soybeanjs](https://github.com/soybeanjs/eslint-config) : Configuration prédéfinie ESLint pour SoybeanJS
- [@soybeanjs/materials](https://github.com/soybeanjs/materials) : Répertoire de matériaux pour SoybeanJS
- [@soybeanjs/vite-plugin-vue-page-route](https://github.com/soybeanjs/vite-plugin-vue-page-route) : Plugin de routage pour SoybeanAdmin

## Projets dérivés de SoybeanAdmin

- [electron-mock-admin](https://github.com/lixin59/electron-mock-api) : Système de gestion de Mock API pour aider les développeurs frontaux à implémenter rapidement des mocks d'interfaces.
- [T-Shell](https://github.com/TheBlindM/T-Shell) : Émulateur de terminal et client SSH avec une interface configurables.

## Aperçu en ligne

- [Adresse de prévisualisation de Soybean Admin](https://admin.soybeanjs.cn/)

## Documentation

- [Adresse de prévisualisation de la documentation du projet](https://admin-docs.soybeanjs.cn/)


## Référentiels de code

| Référentiel     | Lien GitHub                                                                   | Miroir Gitee                                                               | Aperçu                                                    |
| --------------- | ----------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------- |
| soybean-admin   | [GitHub](https://github.com/honghuangdc/soybean-admin)                        | [Gitee](https://gitee.com/honghuangdc/soybean-admin)                      | [Aperçu](https://admin.soybeanjs.cn/)                       |
| Version Tauri   | [Version Tauri](https://github.com/honghuangdc/soybean-admin/tree/tauri)     | [Version Tauri](https://gitee.com/honghuangdc/soybean-admin/tree/tauri) |                                                              |
| Version allégée | [Version allégée](https://github.com/honghuangdc/soybean-admin/tree/thin)    | [Version allégée](https://gitee.com/honghuangdc/soybean-admin/tree/thin) |                                                              |
| Intégration de fast-crud | [Intégration de fast-crud](https://github.com/honghuangdc/soybean-admin/tree/fast-crud) | [Intégration de fast-crud](https://gitee.com/honghuangdc/soybean-admin/tree/fast-crud) | [Aperçu](http://fast-crud.docmirror.cn/soybean/#/crud/demo) |

## Journal des mises à jour

[CHANGELOG](./CHANGELOG.md)

## Services back-end

- [soybean-admin-java](https://github.com/honghuangdc/soybean-admin-java)

## Captures d'écran du projet

![Capture d'écran 1](https://s2.loli.net/2022/05/16/keOtgFH27r9nqYS.png)
![Capture d'écran 2](https://s2.loli.net/2022/05/18/bW7mftiQexkvSTG.png)
![Capture d'écran 3](https://s2.loli.net/2022/05/16/uV5nzjb3gYptAEl.png)
![Capture d'écran 4](https://s2.loli.net/2022/05/16/rSnNHLdpuvkKxWq.png)
![Capture d'écran 5](https://s2.loli.net/2023/06/07/O39EKNa675FZIuS.png)
![Capture d'écran 6](https://s2.loli.net/2022/05/18/Mt6YZqmDxO8v4uR.png)
![Capture d'écran 7](https://s2.loli.net/2023/06/07/zhmWnFlPTfDpot8.png)
![Capture d'écran 8](https://s2.loli.net/2022/05/16/VPl6Ru1iCAhLcS4.png)
![Capture d'écran 9](https://s2.loli.net/2023/06/07/n6Dy1HXBvuPc9oT.png)
![Capture d'écran 10](https://s2.loli.net/2022/06/07/rY8TyAftM5dxspv.png)
![Capture d'écran 11](https://s2.loli.net/2022/06/07/5GNBAd31IzQVjLP.png)
![Capture d'écran 12](https://s2.loli.net/2022/06/07/rRSG6mEZpujOACT.png)
![Capture d'écran 13](https://s2.loli.net/2023/06/07/A5Nonc9vI6pB1lr.png)
![Capture d'écran 14](https://s2.loli.net/2023/06/07/VwBjqEhTke3OxXF.png)


<div align="center">
	<img style="width:380px;margin-right:18px;border:1px solid #dedede;" src="https://s2.loli.net/2023/06/07/A5Nonc9vI6pB1lr.png" />
	&nbsp;
	<img style="width:380px;border:1px solid #dedede;" src="https://s2.loli.net/2023/06/07/VwBjqEhTke3OxXF.png" />
</div>

## 安装使用

- 环境配置
  **本地环境需要安装 pnpm 7.x 、Node.js 14.18+ 和 Git**

- 克隆代码

```bash
git clone https://github.com/honghuangdc/soybean-admin.git
```

- 安装依赖

```bash
pnpm i
```

- 运行

```bash
pnpm dev
```

- 打包

```bash
pnpm build
```

## Docker 部署

- Docker 部署 Soybean

```bash
docker build -t soybean-admin-image -f docker/Dockerfile .
docker run -d -p 80:80 soybean-admin-image
```

- 访问 SoybeanAdmin

打开本地浏览器访问`http://localhost`

## 如何贡献

非常欢迎您的加入！[提一个 Issue](https://github.com/honghuangdc/soybean-admin/issues/new) 或者提交一个 Pull Request。

## Git 贡献提交规范

项目已经内置 Angular 提交规范，直接执行 commit 命令即可生成符合 Angular 提交规范的 commit。

项目已用 simple-git-hooks 代替了 husky, 旧版本用了 husky，执行 pnpm soy init-simple-git-hooks 进行初始化配置

## 浏览器支持

本地开发推荐使用`Chrome 90+` 浏览器

支持现代浏览器, 不支持 IE

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png" alt="IE" width="24px" height="24px"  />](http://godban.github.io/browsers-support-badges/)IE | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt=" Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)Safari |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                                                                                not support                                                                                                                |                                                                                          last 2 versions                                                                                          |                                                                                               last 2 versions                                                                                                |                                                                                             last 2 versions                                                                                              |                                                                                             last 2 versions                                                                                              |

## 开源作者

[@Soybean](https://github.com/honghuangdc)

## 交流

`Soybean Admin` 是完全开源免费的项目，在帮助开发者更方便地进行中大型管理系统开发，同时也提供微信和 QQ 交流群，使用问题欢迎在群内提问。

  <div style="display:flex;">
  	<div style="padding-right:24px;">
  		<p>QQ交流群</p>
      <img src="https://i.loli.net/2021/11/24/1J6REWXiHomU2kM.jpg" style="width:200px" />
  	</div>
		<div>
			<p>添加本人微信，欢迎来技术交流，业务咨询</p>
			<img src="https://s2.loli.net/2023/06/07/sVyCUFBvzQ9f5b7.jpg" style="width:200px" />
		</div>
  </div>

## 捐赠

如果你觉得这个项目对你有帮助，可以请 Soybean 喝杯饮料表示支持，Soybean 开源的动力离不开各位的支持和鼓励。

![赞助](https://s2.loli.net/2022/01/24/i9cpq7lTCrKUoFf.png)

## License

本项目基于[MIT © Soybean-2021](./LICENSE) 协议，仅供参考学习，商用时请保留作者的版权信息，作者不对软件做担保和负责。

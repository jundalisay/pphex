Translate to Arabic, Chinese Simplified, Spanish, French, Japanese:
True Economic Democracy. Pantrypoints implements trisactions in order to create an Economy-as-a-Service or EaaS platform to create "True Economic Democracy".
Register in the Waitlist. Read about the details. 
This is based on the requirements in Book 5, Chapter 2 of Plato's Republic.
'The Points Economy'. Instead of money, Pantrypoints uses points which are pegged to the retail price of grains. This will allow easier points-taxation, points-accounting and analytics, while eliminating the need for money for transactions.
Loyalty Points. These are points given by businesses to their customers to incentivize repeat purchases. This is used to ’train’ people in the use of points.
Donation Points. These are points used for donations and disaster relief. We use this primarily to incentivize 'food rescue' and plastic waste collection in order to realize a moneyless circular economy.
Exchange Points. These are points for barter transactions. Unlike donations points which do not seek something in return, trade points do. This is the foundation of Points-banking.
Investment Points. These are exchange points designed to attract investments when money is lacking. This requires the other point-types to be working beforehand.
Insurance Points. These are exchange points for long-term claim, upon old age. We implement this as social insurance in case money-based insurance becomes oppressive.
Energy Points. These are exchange points for electricity, usually from biomass sources. This incentivizes waste segregation and is part of the circular economy.
Money Points. These are exchange points paid in money to reduce existing trade-points balances.
Cross Points. These are exchange points used for cross-border transactions. These are 'weighted' to prevent imbalances in trade. 
Tax Points. These are exchange points given by users to the government.
Current Implementations. The Pantrypoints system is currently being tested by the following
SCENAC is testing Point Cards as a moneyless social insurance system
Angel’s Shelter is an animal shelter that uses Pantrypoints Build to get moneyless donations
Savilas Vietnam is a new seafood buyer that will test exports via Pantrypoints World
Food Rescue Philippines is a volunteer group that will test Pantrypoints Circle for incentivizing food donations
Do you want to Try Points?


Translate to Arabic, Chinese Simplified, Spanish, French, Japanese:
Bank the Unbanked. Pantrypoints Banking is a low-cost moneyless banking system that circulates the economy that is unserved by the financial system
Based on the requirements in 'The Wealth of Nations' by Adam Smith
Inspired by the Moneyless, Paperless system of the Inca
Points-banking allows the regulated transfer of points between users
Moneyless Ok! Points Banking allows economies to function even after a total financial collapse
Decentralized. A crisis in one place will not affect others.
Flexible. Points Banking can work offline and does not use blockchain
Asynchronous. Users do not need to fulfill their part of the transaction immediately
Cost Effective. Points Banking can be deployed on the cloud to reduce costs
Integrates with Taxation. Points Banking will integrate with Pointtax to allow tax payments in kind
1 Gain points with other users
2 Transfer your points to other users to gain access to their goods and services
3 Use your points as usual
Top 5 in the Fintech Edition as Debt Clearing System
2nd Place as Social ROSCA



{{- with $.Params.images -}}
{{- range first 6 . }}<meta property="og:image" content="{{ . | absURL }}" />{{ end -}}
{{- else -}}
{{- $featured := "" }}
{{- with $featured -}}
<meta property="og:image" content="{{ $featured.Permalink }}"/>
{{- else -}}
{{- with $.Site.Params.images }}<meta property="og:image" content="{{ index . 0 | absURL }}"/>{{ end -}}
{{- end -}}
{{- end -}}


<div align="center">
  <h1 align="center">Hextra</h1>
  <p align="center">Modern, responsive, batteries-included Hugo theme for creating beautiful static websites.</p>

Demo → [imfing.github.io/hextra](https://imfing.github.io/hextra/)
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/5097752/263550533-c18343ca-3848-4230-b5c0-ee989d7916da.png">
  <img alt="Hextra" src="https://user-images.githubusercontent.com/5097752/263550528-663599f9-17a1-4686-b5c4-3da233b5034d.png">
</picture>

<div align="right">
<a href="https://github.com/imfing/hextra/actions/workflows/pages.yml"><img alt="GitHub Actions Status" src="https://github.com/imfing/hextra/actions/workflows/pages.yml/badge.svg"></a> <a href="https://app.netlify.com/sites/hugo-hextra/deploys"><img alt="Netlify Status" src="https://api.netlify.com/api/v1/badges/61d6e55a-2447-487e-b59f-c9537e5df175/deploy-status"></a>
</div>

## Features

- **Beautiful Design** - Inspired by Nextra, Hextra utilizes Tailwind CSS to offer a modern design that makes your site look outstanding.
- **Responsive Layout and Dark Mode** - It looks great on all devices, from mobile, tablet to desktop. Dark mode is also supported to accomodate various lighting conditions.
- **Fast and Lightweight** - Powered by Hugo, a lightning-fast static-site generator housed in a single binary file, Hextra keeps its footprint minimal. No Javascript or Node.js are needed to use it.
- **Full-text Search** - Built-in offline full-text search powered by FlexSearch, no additional configuration required.
- **Battery-included** - Markdown, syntax highlighting, LaTeX math formulae, diagrams and Shortcodes elements to enhance your content. Table of contents, breadcumbs, pagination, sidebar navigation and more are all automatically generated.
- **Multi-language and SEO Ready** - Multi-language sites made easy with Hugo's multilingual mode. Out-of-the-box support is included for SEO tags, Open Graph, and Twitter Cards.

## Quick Start

### Use the template

Using the [Hextra Starter Template](https://github.com/imfing/hextra-starter-template) is the simplest method to bootstrap a new website with Hextra theme. Get started by clicking the "Use this template" button on the template repository page.

The template repository also includes a [GitHub Actions workflow](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow) for deploying your website to GitHub Pages.

<img alt="Hextra Starter Template" src="https://user-images.githubusercontent.com/5097752/263551418-c403b9a9-a76c-47a6-8466-513d772ef0b7.jpg" width=600/>

### Usage

Refer to the [documentation](https://imfing.github.io/hextra/docs) for more information.

## Contributing

Contributions are welcome!
Check out the [contributing guide](.github/CONTRIBUTING.md) to get started.

## License

[MIT License](./LICENSE)

# Awesome Aragon List

> A list of awesome Aragon stuff!

<br>

## Aragon 101

High level intro to Aragon goes here.

- [Wiki](https://wiki.aragon.org) - All the things.
- [Permissions](https://aragon.helpscoutdocs.com/article/21-permissions) - Explains how permissions work on Aragon.
- [Aragon User Guide](https://wiki.aragon.org/tutorials/Aragon_User_Guide/) - Now on help.aragon.org.
- [Aragon Apiary](https://apiary.1hive.org/) - Like a block explorer, but for Aragon DAOs. Lists DAOs based on how lively they are (AUM and activity).

<br>

## 🧰 Hacking On Aragon

Tools and guides to build awesome Aragon stuff.

- [Docs](https://hack.aragon.org/docs/getting-started) - All the things.
- [AragonCLI](https://hack.aragon.org/docs/cli-dao-commands) - A CLI tool for Aragon stuff.
- [Frame](https://github.com/floating/frame) - Does Frame have docs?

<br>

## 📜 Tutorials

How to Aragon.

- [App Development Guide](https://hack.aragon.org/docs/tutorial)
- [App Publishing Guide](https://hack.aragon.org/docs/guides-publish)
- [Deploying Custom Organizations](https://hack.aragon.org/docs/guides-custom-deploy)

<br>

## 🍱 Aragon DAO Templates

Aragon DAO design patterns that are easy to deploy.

- [Dandelion Orgs](https://1hive.org/getting-started-with-dandelion-organizations/) - MolochDAO V2 on Aragon minus rage-kick.
- [Aragon Fundraising](https://fundraising.aragon.black/) - A clasic [DAICO](https://ethresear.ch/t/explanation-of-daicos/465) model on Aragon.
- [Aragon Classic](https://mainnet.aragon.org/#/create) - The Company, Reputation, and Membership orgs are the same template (token manager, vault, and voting apps) with slightly differnent restrictions on token transfers.

<br>

## 📱 Aragon Apps

Apps you can plug into your Aragon DAO.

### 💱 Tokens & Financial Stuff

- [Token manager](https://aragon.helpscoutdocs.com/article/18-token-manager) - An app that creates and manages tokens that can be used in Aragon DAOs.
- [Vault](https://github.com/aragon/aragon-apps/tree/master/apps/vault) - A vault that can be configured to be managed by DAO token holders (requires using [Finance](https://aragon.helpscoutdocs.com/article/20-finance) app as a front-end).
- [Finance](https://aragon.helpscoutdocs.com/article/20-finance) - A front-end for the [Vault](https://github.com/aragon/aragon-apps/tree/master/apps/vault) app.
- [Agent](https://aragon.org/agent) - A "smart vault" that allows the DAO to act like an externally owned account (EAO). You can send tokens directly to the Agent's contract address and Agent can do anything you can do via Metamask, however, actions are routed through a DAO vote by default (but you can change this just like with any app).
- [Token request](https://github.com/1Hive/token-request-app) - Request DAO tokens in exchange for other tokens (usually ETH or DAI).
- [Redemptions](https://github.com/1Hive/redemptions-app) - Redeem tokens against a basket of white-listed tokens held in the DAO.
- [Projects](https://github.com/AutarkLabs/planning-suite/tree/dev/apps/projects) - An app that allows the DAO to award bounties for working on GitHub Issues.
- [Allocations](https://github.com/AutarkLabs/planning-suite/tree/dev/apps/allocations) - Allows the DAO to set a budget of tokens to allocate on a weekly basis.
- [Rewards](https://github.com/AutarkLabs/planning-suite/tree/dev/apps/rewards) - Dividends for DAO members.
- [Payroll](https://github.com/aragon/aragon-apps/tree/master/future-apps/payroll) - Recurring payments from the DAO.

### ☑ Governance

- [Survey](https://github.com/aragon/aragon-apps/tree/master/apps/survey) - Signalling votes for DAO token holders.
- [Voting](https://aragon.helpscoutdocs.com/article/19-voting) - The default voting app that ships with most Aragon DAOs.
- [Conviction voting](https://github.com/1Hive/conviction-voting-app/) - Continuous voting that allows users to signal their preferences among numerous proposals. More info [here](https://medium.com/giveth/conviction-voting-a-novel-continuous-decision-making-alternative-to-governance-aa746cfb9475).
- [Dandelion voting](https://github.com/1Hive/dandelion-voting-app) - Like the reg voting app, but votes are put in a que and information on who voted on what can be connected into other Aragon apps (mainly within [the Dandelion suite](https://1hive.org/getting-started-with-dandelion-organizations/)).
- [Dot Voting](https://github.com/AutarkLabs/planning-suite/tree/dev/apps/dot-voting) - Dot voting for DAOs (only works for signalling or distribution of allocations)
- [Furarchy](https://github.com/levelkdev/futarchy-app) - Futarchy markets for governance.
- [Delay](https://github.com/1Hive/delay-app/blob/master/docs/user-guide.md) - The Delay app is a [forwarder](https://hack.aragon.org/docs/forwarding-intro). It can delay, pause, and resume an action initiated by a DAO member.
- [Aragon agreements](https://aragon.org/agreements) - Operating agreements for DAOs. Members can refer to this doc in arbitration if they raise a dispute around a DAO action.
- [SVRP](https://github.com/aragon/svrp) - Simplified voting relayer protocol (layer 2 voting) for Aragon DAOs.
- [Voting connectors](https://github.com/aragonone/voting-connectors) - Stuff to wrap and/or connect non [MiniMe tokens](https://github.com/giveth/minime) to Aragon voting apps. 
  - [Voting aggregator](https://github.com/aragonone/voting-connectors/blob/master/apps/voting-aggregator) - Aggregate voting power over multiple sources.
  - [Token wrapper](https://github.com/aragonone/voting-connectors/tree/master/apps/token-wrapper) - Wrap any ERC-20 token to be used in Aragon voting apps.

### 🤖 Other Stuff

- [MyID](https://github.com/MyBitFoundation/MyBit-DAO.tech/tree/master/apps/MyID) - No idea. Please submit a PR if you figure it out.
- [MyTokens](https://github.com/MyBitFoundation/MyBit-DAO.tech/tree/master/apps/MyTokens) - No idea. Please submit a PR if you figure it out.
- [Livepeer Transcoder Manager](https://github.com/videoDAC/livepeer-aragon) - This app empowers a "Decentralized Autonomous Organisation" (DAO) on Aragon's platform to govern the roles of Delegator and Transcoder in Livepeer's protocol.
- [DappNode NFT Manager](https://github.com/eduadiez/DAppNodeNFT) - No idea. Please submit a PR if you figure it out.
- [Espresso](https://github.com/espresso-org/aragon-drive) - Espresso Drive is an application that allows easy file storing and sharing within your Aragon DAO. It is a decentralized alternative to apps like Google Drive and Dropbox.
- [MESG](https://github.com/mesg-foundation/aragon) - This application allows you to connect any events from your organisation to external services to be notified in real-time.
- [Staking](https://github.com/aragon/staking) - The main motivation is to be used in conjunction with [Agreements](https://github.com/aragon/aragon-apps/tree/master/apps/agreement) in the context of Aragon Network, but it has been designed to be as generic as possible, in order to allow for other use cases too.
- [Use wallet](https://github.com/aragon/use-wallet) - An SDK to connect a dapp (DAO) to an Ethereum provider (wallet).

<br>

## ✨ DAO UX

Things that improve the experience of using Aragon DAOs.

- [ArgoDisco](https://eth.taxi/blog/dao_notifications) - Discord bot notifications for Aragon events.
- [Tenderly](https://blog.tenderly.dev/how-to-monitor-your-aragon-organization-using-tenderly/) - Analytics and notifications for Aragon DAOs.
- [InfoBot](https://github.com/abridged/info-access-bot) - Open source code to create a Telegram bot that notifies you of voting events on Aragon DAOs.
- [AccessBot](https://github.com/abridged/info-access-bot) - Open source code to create a token permissioned chat on Telegram.
- [Collab19 template](https://github.com/abridged/dao-help) - Open source code to create a Telegram DAO that allows people to buy tokens, create a wallet, and vote on proposals all within a chat interface.
- [HelpDAO donation portal](https://github.com/helpdao/donation-portal) - Integrations with on and off ramps for Aragon DAOs.
- [AraCred](https://github.com/aracred/) - Measure and reward contributions to open source projects and mint tokens proportionally.

<br>

## 🤷 Unorganized

### Organizations that hacked and/or are hacking on Aragon

- [Empower The DAO apps](https://github.com/empowerthedao) - Aragon apps for Uniswap, Livepeer, and more stuff.
- [DAOnuts](https://github.com/daonuts) - Apps for dual-token voting, subscriptions, token claims, and more.
- [1Hive](https://github.com/1hive/) - Apiary DAO explorer, app installer, gardens, dandelion, and more.
- [Open Enterprise](https://github.com/AutarkLabs/open-enterprise) - Open Enterprise is a collection of Aragon apps that enable organizations to curate issues, collectively budget, and design reward and bounty programs.
- [P2P Models](https://github.com/p2pmodels) - A set of apps organized around document editing.
- [Aragon](https://github.com/aragon/) - All the stuff that Aragon One worked on. Includes some apps, but mostly core infra.
- [LexDAO](https://github.com/lexDAO) - Pushes forward the cutting edge of Aragon DAOs and DAO to DAO interactions via Agent.
- [HelpDAO](https://github.com/helpdao/) - Making it easy to spin up DAOs to receive and distribute donations.
- [AraCred](https://github.com/aracred/) - Measuring and rewarding contributions to projects with DAO tokens.

### Delegated voting explorations

- https://github.com/aragon/labs/issues/3
- https://github.com/1Hive/Hive-Democracy
- https://github.com/aragon/aragon-apps/pull/881

### Requests for Aragon apps

- https://forum.aragon.org/c/product/requests

---
description: Network explorers hosted by the community
cover: >-
  ../.gitbook/assets/Hero-Desktop-NetworkExplorers_2022-12-07-020704_ehza
  (1).webp
coverY: -209.48275862068965
---

# Network Explorers and Tools

Hedera network explorers are tools for tracking activity on the Hedera network. Mirror nodes provide real-time data on transactions, while network explorers offer a user-friendly interface for viewing and searching those transactions.

Check out some of the community-hosted network explorer services listed below. Each community-hosted network explorer may have their own unique features and experience.

<table data-card-size="large" data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden></th><th data-hidden></th></tr></thead><tbody><tr><td align="center"><a href="https://explorer.arkhia.io/#/mainnet/dashboard"><mark style="color:purple;"><strong>NETWORK EXPLORER</strong></mark></a></td><td></td><td></td><td><a href="../.gitbook/assets/4.png">4.png</a></td><td><a href="https://explorer.arkhia.io/">https://explorer.arkhia.io/</a></td><td></td><td></td></tr><tr><td align="center"><a href="https://app.dragonglass.me/hedera/home"><mark style="color:purple;"><strong>NETWORK EXPLORER</strong></mark></a></td><td></td><td></td><td><a href="../.gitbook/assets/dragon-glass-logo.png">dragon-glass-logo.png</a></td><td><a href="https://app.dragonglass.me/hedera/home">https://app.dragonglass.me/hedera/home</a></td><td></td><td></td></tr><tr><td align="center"><mark style="color:purple;"><strong>NETWORK EXPLORER</strong></mark></td><td></td><td></td><td><a href="../.gitbook/assets/22.png">22.png</a></td><td><a href="https://hashscan.io/">https://hashscan.io/</a></td><td></td><td></td></tr><tr><td align="center"><a href="https://hederaexplorer.io/"><mark style="color:purple;"><strong>NETWORK EXPLORER</strong></mark></a></td><td></td><td></td><td><a href="../.gitbook/assets/23.png">23.png</a></td><td><a href="https://hederaexplorer.io/">https://hederaexplorer.io/</a></td><td></td><td></td></tr></tbody></table>

## FAQ

<details>

<summary><mark style="color:blue;"><strong>How do I search for a transaction?</strong></mark></summary>

To search for a specific transaction, you can use the unique transaction ID.

The transaction ID should look something like this: `0.0.48750443@1671560120.085845879`

</details>

<details>

<summary><mark style="color:blue;"><strong>How do I get the transaction ID?</strong></mark></summary>

The transaction ID can be automatically generated by the SDK, manually created and associated with a transaction, or obtained from the receipt or record after the transaction has been processed. It serves as a unique identifier for the transaction and can be used to search for and view its details.

</details>

<details>

<summary><mark style="color:blue;"><strong>How do I search for an entity (account, topic, tokens, smart contracts)?</strong></mark></summary>

You can search by the unique ID of the entity you are looking for. The entity ID format is `0.0.entityNumber`.

For example, `0.0.2` is an account ID and you search for that account using that ID.

</details>

<details>

<summary><mark style="color:blue;"><strong>How do I get the entity ID?</strong></mark></summary>

Entity IDs are returned in the receipt of the transaction that created them. Entities include accounts, topics, smart contracts, schedules, and tokens.\
\
For example, if you create a new account using the `AccountCreateTransaction` in the SDK, you can get the new account ID from the transaction receipt.

</details>

<details>

<summary><mark style="color:blue;"><strong>Can I host my own Hedera network explorer?</strong></mark></summary>

Yes, you can! You can create your own custom Hedera network explorer using the [Mirror Node REST APIs](../sdks-and-apis/rest-api/) or take a look at the [Hedera Mirror Node Explorer](https://github.com/hashgraph/hedera-mirror-node-explorer) open-source project.

</details>

<details>

<summary><mark style="color:blue;"><strong>How can I add a network explorer to this page?</strong></mark></summary>

To add a network explorer to this page, refer to the [contributing guide](../support-and-community/contributing-guide.md) and open an issue in the `hedera-docs` [repository](https://github.com/hashgraph/hedera-docs). Please include the following information within the issue:

* Network explorer name
* Link to network explorer
* High-resolution logo

</details>

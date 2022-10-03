---
layout: blocks
title: Fair Data Protocol
date: 2017-11-22T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2022/10/03/fds_logo_square_white-4x-80-cropped.jpg"
  navigation:
  - link: https://gitcoin.co/fairdatasociety
    link_text: Bounties
  - link: https://www.youtube.com/watch?v=pxYk552e4js&list=PL6fQnFAjtuY-vzfZgSF5UjP88rM89MV8X
    link_text: Videos
  - link: https://fairdatasociety.bzz.link
    link_text: Blog
  - link: https://www.ethswarm.org/jobs
    link_text: Jobs
  cta:
    url: https://github.com/fairDataSociety
    button_text: GitHub
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: Fair Data Protocol
  content: Developed under Fair Data Society, Fair Data Protocol aims to provide web3
    storage for dApps to connect and use, allowing for fair access and re-use of data
    on a global scale.
  cta:
    enabled: true
    url: https://github.com/fairDataSociety
    button_text: 'See on GitHub '
  image:
    image: ''
    alt_text: ''
  background_image: "/uploads/2022/06/11/ferdinand-stohr-nfs6drtbgam-unsplash.jpeg"
- template: 3-column-text
  block: three-column-1
  col_1:
    slug: ''
    content: Fair Data Protocol interoperability has several layers, where independence
      from a data providers open up new opportunities to share and reuse data.
    headline: Interoperability
  col_2:
    headline: 'Self Sovereignty '
    slug: ''
    content: Fair Data Protocol enables independence from clouds and data silos by
      relying on the network of peers to host the data giving end users ultimate control.
  col_3:
    headline: Privacy
    slug: ''
    content: Fair Data Protocol enables a private space in the decentralized cloud,
      the prerequisite for digital freedom.
- template: content-feature
  block: feature-1
  media_alignment: Right
  content: Fair Data Protocol provides various libraries and tools for developers
    to build using it. <br><br>The underlying storage is FairOS-dfs, based on Swarm
    decentralized storage. It can be accessed through browser libraries or a dedicated
    client.<br><br>Blossom is a browser extension that allows dApps to access the
    personal storage of users. By integrating with its framework, the wallet handling
    is no longer a question for dApps and users have single-sign-in (SSI) to log in
    their account.<br><br>Various other libraries are provided for more special use
    cases. <strong><br><br>FDP Play</strong><br>FDP Play is entry point for developers
    to start building with FDP - a CLI tool to spin up local development FDP environment
    with Docker. It includes a Bee cluster, FairOS instance and blockchain node. The
    GitHub code and instructions are <a href="https://github.com/fairDataSociety/fdp-play"
    title="">here</a>. Click and press play!<br>
  headline: Fair Data Protocol Toolkit
  slug: ''
  media:
    image: "/uploads/2022/06/11/shubham-dhage-uxdu0gg5pqq-unsplash.jpeg"
    alt_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: customize
  headline: FairOS
  content: '<strong>FairOS-dfs</strong><br>FairOS-dfs is a layer on top of Swarm decentralized
    storage, that offers more advanced data structures - drive, folder and files hierarchy;
    a key value store and a document store. For implementation in Golang the documentation
    is <a href="https://docs.fairos.fairdatasociety.org/docs/" title="">here</a>.<br><br><strong>FDP
    Storage</strong><br>FairOS-dfs implementation in JavaScript, can be run in browsers.
    You can access the GitHub <a href="https://github.com/fairDataSociety/fdp-storage"
    title="fdp-storage">here</a>.<br><br><strong>FairOS in WASM</strong><br>FairOS-dfs
    library in WASM. You can access the GitHub <a href="Fairdrive is a dApp that enables
    decentralized storage on Swarm. It consists of a typical &quot;Drive&quot; interface
    with files and folders, and a BZZ wallet to manage token balances and keypairs.
    " title="">here</a>.<br><br><strong>FairOS Connect</strong><br>A set of convenience
    components that can be included in dApps to support FairOS. These components were
    used in the reference Fairdrive App. You can access the GitHub<span class="Apple-converted-space">
    </span><a href="https://github.com/fairDataSociety/fairos-connect/" title="">here</a>.   '
  media:
    image: "/uploads/2022/06/11/blockchain-3d-image.jpeg"
    alt_text: Customize Blocks
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: Blossom
  content: Blossom browser extension serves as a framework for Fair Data Protocol
    developers and an environment for Web3 users acting as their user agent allowing
    Single Sign In. It provides complete traceless Web3 browsing, handles the user
    wallet and provides a FDP Storage interface for managing the User Personal Storage
    for dApps.<br>You can access the GitHub documentation <a href="https://github.com/fairDataSociety/blossom"
    title="Blossom repo">here</a>.
  slug: ''
  media:
    image: "/uploads/2022/06/11/shubham-dhage-uxdu0gg5pqq-unsplash.jpeg"
    alt_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Applications
  content: Application ecosystem around Fair Data Protocol is growing daily. Below
    are a few applications that might inspire you to develop your own.<strong><br><br>Fairdrive<br></strong>Fairdrive
    is a dApp that opens the self-sovereign cloud to the individual users. It consists
    of a typical "Drive" interface with files and folders, making it convenient for
    end users. You can access the GitHub<span class="Apple-converted-space"> </span><a
    href="https://github.com/fairDataSociety/fairdrive-theapp" title="">here</a>.
    Read more and try it out by going to Fairdrive <a href="https://fairdrive.fairdatasociety.org/"
    title="Fairdrive">page</a>.<br><br><strong>FairPass<br></strong>A decentralized
    password manager built with FairOS on top of Swarm storage. It can save "passwords"
    and "notes" and works for desktop and mobile. You can access the GitHub<span class="Apple-converted-space">
    </span><a href="https://github.com/fairDataSociety/FairPass" title="">here</a>.
  slug: ''
  media:
    image: "/uploads/2022/06/11/blockchain-3d-image.jpeg"
    alt_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: BeeSon
  content: BeeSon is a JSON compatible serialization format which allows its elements
    to be verified cheaply on-chain. You can access the GitHub <a href="https://github.com/fairDataSociety/beeson"
    title="BeeSon repo">here</a>.
  slug: ''
  media:
    image: "/uploads/2022/06/11/shubham-dhage-uxdu0gg5pqq-unsplash.jpeg"
    alt_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Fair Data Improvement Proposals
  content: The Fair Data Protocol improvement proposal (FIP) process is intended to
    provide a path for new specifications and features to be added to the Fair Data
    Protocol. This provides all the stakeholders with option to influence the direction
    the Fair Data Protocol evolution. The FIP process is described in the GitHub <a
    href="https://github.com/fairDataSociety/FIPs" title="FIPs repo">repo</a>.
  slug: ''
  media:
    image: "/uploads/2022/06/11/blockchain-3d-image.jpeg"
    alt_text: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Other Tools
  slug: ''
  content: '<strong>FDP Contracts</strong><br>Contracts used in development, including
    BMT contracts and ENS contracts. <br><br><span style="text-decoration: underline;">BMT
    Contracts</span> - Swarm hashes can be verifiable on chain via Binary Merkle Trees.
    Fair Data Protocol has a full data function and coordinating JS library to support
    this. You can access the GitHub documentation<span class="Apple-converted-space">
    </span><a href="https://github.com/fairDataSociety/bmt-js" title="">here</a>.<br><br><span
    style="text-decoration: underline;">ENS Contracts</span> - A reserved ENS name
    with an associated ETH address is used for Fair Data Protocol accounts. You can
    access the GitHub documentation<span class="Apple-converted-space"> </span><a
    href="https://github.com/fairDataSociety/fdp-contracts/tree/master/js-library"
    title="">here</a>.<br><br><strong>FDP Processor Library</strong><br>Beeson - A
    Blockchain-verifiable, extensible encapsulation for schema-based object notation
    in Swarm. You can access the GitHub documentation<span class="Apple-converted-space">
    </span><a href="https://github.com/fairDataSociety/beeson" title="">here</a>.  '
  media:
    image: "/uploads/2022/06/11/markus-spiske-mgthz4zlc1u-unsplash.jpeg"
    alt_text: ''
- template: 4-column-footer
  block: footer-2
  col_2: <a href="https://github.com/fairDataSociety" title="GitHub"><img src="/uploads/2022/10/03/github-mark-32px.png"></a>
  col_4: <a href="https://twitter.com/fairdatasociety" title="Twitter"><img src="/uploads/2022/10/03/twitter.svg"></a>
  col_3: <a href="https://discord.gg/RpX5eU4Cpr" title="Discord"><img src="/uploads/2022/10/03/discordpurple.svg"></a>
  image: "/uploads/2022/06/11/fdp-logo-only.png"
- template: simple-footer
  block: footer-1
  content: <strong>Enabled by</strong><br><br><a href="https://www.ethswarm.org/"
    title="Swarm"><img src="/uploads/2022/10/03/swarm.svg"></a><br><br><a href="https://fairdatasociety.org/"
    title="Fair Data Society"><img src="/uploads/2022/10/03/fairdata.svg"></a><br>

---

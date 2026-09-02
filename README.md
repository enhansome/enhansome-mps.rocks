# Awesome MPS rocks with stars

A curated list of awesome MPS extensions/libraries, software and resources.

Inspired by [awesome-python](https://github.com/vinta/awesome-python/) ⭐ 317,938 | 🐛 16 | 🌐 Python | 📅 2026-09-01 and [awesome-rust](https://github.com/rust-unofficial/awesome-rust) ⭐ 59,113 | 🐛 8 | 🌐 Rust | 📅 2026-09-02.

## What are you looking for?

### Understand what MPS is

* [What is MPS and why to build your own language](https://www.youtube.com/watch?v=9BvpBLzzprA)

### See what others have been building with MPS

* [Built with MPS](#built-with-mps) are open source projects that all built on MPS
* [Research](#research) contains a list academic papers that make heavy use of MPS

### Get started with MPS

To get stated we suggest to look at the tutorials in the following order:

* [MPS for the Impatient](https://stepik.org/course/71593/) is a free hands-on course that covers the basics of JetBrains MPS from the language designer's perspective, skipping the theoretical topics as well as the practical productivity how-tos.
* [HeayMeta.tv](https://heavymeta.tv) - A complete MPS tutorial to build your first language by @coolya with lots background information on language design.
* [MPS Intro Course by @markusvoelter](https://github.com/markusvoelter/mpsintrocourse) ⭐ 43 | 🐛 2 | 🌐 JetBrains MPS | 📅 2026-08-23 is an advanced introduction to MPS in the form of multiple videos as well as a github repository to play around with. It also covers extensions to MPS such as additional notations or the interpreter framework.
* If you are specificity looking for input on how to build generators [this guide](https://coolya.github.io/maintainable-generators/) contains a set of best practices.
* The [DSL Engineering Book](http://dslbook.org/) contains detailed discussions of the concepts behind MPS in its Part III on language implementation.
* For more details on specific MPS topics we refer to The MPS Language Workbench Book ([Volume I](https://www.amazon.com/dp/B00JFFIR1U/), [Volume II](https://www.amazon.com/dp/B01GOHUEPS/)) as well as the official [MPS User Guide](https://www.jetbrains.com/help/mps/mps-user-s-guide.html)

[Learning](#learning-mps) contains a list of even more tutorials. In addition [Research](#research) contains a list academic papers that make heavy use of MPS.

### Get in touch with the community

* The [Community](#community) list the usual suspects

## [Awesome MPS](#awesome-MPS)

### Plugins

Plugins that improve MPS.

* [MPS Extensions](https://github.com/JetBrains/MPS-extensions) ⭐ 88 | 🐛 126 | 🌐 JetBrains MPS | 📅 2026-09-02 - Various extensions to simplify language development.
* [ingrid](https://github.com/premun/ingrid) ⭐ 24 | 🐛 2 | 🌐 Java | 📅 2019-08-15 - Ingrid is a plugin for JetBrains MPS allowing import of ANTLRv4 grammars and create an MPS language out of it.
* [mps-code-reviewer](https://github.com/Workday/mps-code-reviewer) ⭐ 16 | 🐛 7 | 📅 2023-04-08 - Code Review for JetBrains MPS providing integration with Bitbucket
* [MPS gradle plugin](https://github.com/mbeddr/mps-gradle-plugin) ⭐ 16 | 🐛 28 | 🌐 Kotlin | 📅 2026-08-20 - A Gradle plugin to build & test langauges and to support various tasks related to custom RCP packaging.
* [Editor2PDF](https://github.com/CampagneLaboratory/Editor2PDF) ⭐ 10 | 🐛 2 | 🌐 Java | 📅 2018-05-24 - Serialises editor into PDF files
* [Durchblick](https://github.com/coolya/Durchblick) ⭐ 9 | 🐛 6 | 🌐 JetBrains MPS | 📅 2024-08-06 - Simplified editors to increase readability of generators.
* [MPS-QA](https://github.com/mbeddr/mps-qa) ⭐ 9 | 🐛 11 | 🌐 JetBrains MPS | 📅 2026-09-02 - This repository contains quality assurance tooling for Jetbrains' MPS.
* [skadi gist](https://github.com/skadi-cloud/gist) ⭐ 6 | 🐛 26 | 🌐 Kotlin | 📅 2026-03-09 - Share MPS code snippets via the browser.
* [Stubs Generator](https://github.com/wirthma/StubsGenerator) ⭐ 2 | 🐛 0 | 🌐 JetBrains MPS | 📅 2023-04-05 - Stubs Generator is a plugin to Jetbrains MPS which allows easy creation of generators of library stubs for custom MPS languages.
* [digitalember.extensions](https://github.com/digital-ember/digitalember.extensions) ⭐ 1 | 🐛 0 | 📅 2018-03-31 - MPS baseLanguage editor extensions for better readability.
* [Build Script Notifier](https://plugins.jetbrains.com/plugin/15203-build-script-notifier) - Fix your build scripts with one click when module dependencies change.
* [Fernsprecher](https://plugins.jetbrains.com/plugin/15633-fernsprecher) - View your IntelliJ based IDE logs directly in your browser.
* [Grammar Cells](http://mbeddr.com/files/gc-sle.pdf) - An extension to the editor language of MPS. It will help you to create consistent and well-behaving textual notations in MPS with no effort.
* [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x) - This plugin helps to learn essential shortcuts while you are working.
* [langdoc](https://plugins.jetbrains.com/plugin/12325-langdoc) - This plugin allows arbitrary nodes in your models to be annotated with documentation text.
* [Language visualizer](https://jetbrains.github.io/MPS-extensions/extensions/langvis) - A JetBrains MPS plugin to visualize the structure of a language.
* [Mario Progress Bar](https://plugins.jetbrains.com/plugin/14708-mario-progress-bar) - Pretty progress bars for IJ based IDEs.
* [MPS BaseLanguage Extensions](https://plugins.jetbrains.com/plugin/7101-mps-baselanguage-extensions) - A set of handy extensions to BaseLanguage, such as tail recursion optimization and function memoization
* [Nyan Progress Bar](https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar) - Pretty progress bars for IJ based IDEs.
* [Presentation Assistant](https://plugins.jetbrains.com/plugin/7345-presentation-assistant) - This plugin shows name and Win/Mac shortcuts of any action you invoke.
* [Shadow Models](https://voelter.de/data/pub/SLE2019.pdf) - Shadow Models is an incremental transformation framework
  for MPS.
* [Text Generator Plugin](https://jetbrains.github.io/MPS-extensions/extensions/plaintext-gen/) - Alternative Textgen for JetBrains MPS using the standard model to model generation mechanisms.

## [Built with MPS](#built-with-mps)

### IDEs

Complete IDEs built with MPS.

* [mbeddr](https://github.com/mbeddr/mbeddr.core) ⭐ 233 | 🐛 86 | 🌐 JetBrains MPS | 📅 2026-09-02 - An extensible C implementation in MPS to support embedded software development.
* [FBME](https://github.com/JetBrains/fbme) ⭐ 23 | 🐛 14 | 🌐 JetBrains MPS | 📅 2026-05-13 - FBME (Function Blocks Modelling Environment) is an IDE for IEC 61499 standard built on top of JetBrains MPS language workbench.
* [PeoPL](https://github.com/benbehringer/peopl) ⭐ 5 | 🐛 20 | 🌐 Java | 📅 2022-05-20 - A full IDE build upon MPS to manage Software Product Lines.
* [Dutch Tax Office](https://resources.jetbrains.com/storage/products/mps/docs/MPS_DTO_Case_Study.pdf) - Domain-specific languages to implement Dutch tax legislation and process changes of that legislation.
* [Hardella IDE](https://hardella.com/en/) - Smart programming environment for PLC
* [MetaR](https://metar-languages.github.io/) - A IDE for R for people with limited computer science background.

### Languages

Individual languages.

* [iets3](https://github.com/iets3/iets3.opensource) ⭐ 53 | 🐛 131 | 🌐 JetBrains MPS | 📅 2026-09-02 - Base language for system modelling and specification including basics abstractions for  components, expression, variability, etc.
* [ecmascript4mps](https://github.com/mar9000/ecmascript4mps) ⭐ 41 | 🐛 1 | 📅 2024-07-03 - ECMAScript language implementation for JetBrains MPS.
* [CsBaseLanguage](https://github.com/vaclav/mpscs) ⭐ 35 | 🐛 0 | 🌐 JetBrains MPS | 📅 2024-11-05 - An implementation of the C# 5.0 language.
* [Voice Menu](https://github.com/vaclav/voicemenu) ⭐ 35 | 🐛 5 | 🌐 JetBrains MPS | 📅 2026-08-31 - A voice menu language and a Java simulator built using JetBrains MPS.
* [ANTLR\_MPS](https://github.com/CampagneLaboratory/ANTLR_MPS) ⭐ 26 | 🐛 4 | 🌐 Java | 📅 2017-09-06 - An ANTLR language for MPS, and the ToMPS language to help create MPS languages and ANTRL visitors from an ANTLR 4 grammar.
* [DclareForMPS](https://github.com/ModelingValueGroup/DclareForMPS) ⭐ 21 | 🐛 26 | 🌐 JetBrains MPS | 📅 2026-08-29 - Support for the dclare engine in MPS.
* [MPS JSON Language](https://github.com/nkoester/mps-json) ⭐ 16 | 🐛 1 | 📅 2018-05-03 - A JSON implementation for MPS.
* [Web languages](https://github.com/dslmeinte/mps-open-source/tree/master/mps-open-source) ⭐ 13 | 🐛 3 | 🌐 JetBrains MPS | 📅 2026-05-21 - a collection of Web-centric, partial language implementations: JSON, JSON Schema, WSDL, XSD, SVG, CSS.
* [FormatsDSL](https://github.com/ftomassetti/FormatsDSL) ⭐ 10 | 🐛 17 | 📅 2023-09-29 - A DSL to describe formats and generate loaders.
* [mbeddr.cpp](https://github.com/DSLFoundry/mbeddr.cpp) ⭐ 5 | 🐛 20 | 🌐 JetBrains MPS | 📅 2026-08-19 - C++ language implementation prototype for JetBrains MPS, built as an extension on mbeddr.core (C language).
* [Physics](https://github.com/vaclav/Physics) ⭐ 5 | 🐛 5 | 🌐 JetBrains MPS | 📅 2024-03-22 - A physical simulation description language built with MPS.
* [D-Flat](https://github.com/DSLFoundry/mps-dflat) ⭐ 4 | 🐛 2 | 🌐 JetBrains MPS | 📅 2026-08-28 - C# language implementation prototype for JetBrains MPS.
* [PlantUML](https://github.com/vjramirez/PlantUML) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2017-06-22 - Language for PlantUML models, also useful to generate PlantUML diagrams from custom DSL.

### Other projects

* [MPSServer](https://github.com/strumenta/mpsserver) ⭐ 21 | 🐛 21 | 🌐 Python | 📅 2023-12-07 - A tool to make MPS accessible remotely.
* [WebEditKit](https://github.com/strumenta/webeditkit) ⭐ 15 | 🐛 36 | 🌐 TypeScript | 📅 2023-09-29 - This is a framework for creating projectional editors which interact with JetBrains MPS.
* [mpsZooKeeper.sh](https://github.com/nkoester/mps-zookeeper) ⭐ 8 | 🐛 1 | 🌐 Shell | 📅 2023-08-10 - Helper script to generate an isolated configuration prefix for isolated MPS instances.
* [Modelix](https://modelix.github.io/) - Modelix is a open source platform that aims to bring modeling on the web.
* [MPS CodeRules](https://jetbrains.github.io/mps-coderules/about) - New typesystem from JetBrains for MPS. Uses logic programming.
* [MPS Platform Docs](http://mbeddr.com/mps-platform-docs/) - This website collects practical knowledge about MPS and popular MPS platforms.
* [Skadi Cloud](https://skadi.cloud/) - An experiment with Projector to put JetBrains MPS into the browser.

## [Learning MPS](#learning-mps)

### [Tutorials / Courses](#Courses)

* [Learn MPS](https://www.jetbrains.com/mps/learn/) - Browse top resources, improve your MPS skills, and connect with the community.
* [Creating a simple language using JetBrains MPS](https://dev.to/antoine/creating-a-simple-language-using-jetbrains-mps-c7d) - The objective of this project is to construct a language to define mindmaps.
* [Fast track tutorial](https://www.jetbrains.com/help/mps/fast-track-to-mps.html) is the official tutorial for MPS. It will provide you with an high-level overview in 10 steps, covering all aspects of MPS at a high level.
* [HeayMeta.tv](https://heavymeta.tv) - A complete MPS tutorial to build your first language by @coolya with lots background information on language design.
* [MPS for the Impatient](https://stepik.org/course/71593/) is a free hands-on course that covers the basics of JetBrains MPS from the language designer's perspective, skipping the theoretical topics as well as the practical productivity how-tos.
* [mps-tips](https://neumantm.github.io/mps-tips/) - Collection of tips and tricks about the MPS ecosystem which might be useful to someone.
* [MPS tutorials](https://www.jetbrains.com/help/mps/mps-tutorials.html) - Official tutorials and cookbooks for MPS.
* [MPS Intro Course by @markusvoelter](https://github.com/markusvoelter/mpsintrocourse) ⭐ 43 | 🐛 2 | 🌐 JetBrains MPS | 📅 2026-08-23 - A slightly advanced introduction to MPS wiht a focus on language extension.
* [MPS Office Hours](https://specificlanguages.com/mps-office-hours/) - A weekly one-hour Zoom meeting where you can share your screen and get help.

### [Books and User Guides](#Guides)

* [Deployment options for MPS](https://www.itemis.com/en/it-services/methods-and-tools/dsls-mps-deployment-options)
* [Domain-Specific Languages in Practice with JetBrains MPS](https://www.springer.com/gp/book/9783030737573#aboutBook) - Provides an overview of the domain of language workbenches and examples in both industrial applications and research projects.
* [DSL Engineering](http://dslbook.org/) - Contains a detailed discussion of the concepts behind MPS in its Part III on language implementation.
* [The MPS Language Workbench](https://www.amazon.com/gp/product/B00JFFIR1U/ref=dbs_a_def_rwt_bibl_vppi_i0) - Introduction to the JetBrains MPS language workbench and a complete reference manual.
* [Towards Maintainable Generators](https://coolya.github.io/maintainable-generators/) - Best practices for maintainable generators and a set of rules when to apply them.
* [MPS OpenAPI Documentation](https://alexanderpann.github.io/mps-openapi-doc/)
* [MPS User Guide](https://www.jetbrains.com/help/mps/mps-user-s-guide.html)

## [Community](#community)

### [Medium](#medium)

* [JetBrains MPS related stories](https://medium.com/search?q=Jetbrains+mps)

### [Twitter](#twitter)

* [JetBrains MPS](https://twitter.com/jetbrains_mps)

### [Slack](#slack)

* [JetBrains MPS slack channel](http://slack-mps.jetbrains.com/)

### [Websites](#websites)

* [DSLFoundry](http://dslfoundry.com/) - DSLFoundry blog: howtos and articles about practical MPS usage.
* [F1RE](https://www.f1re.io/) - A blog focus on the model driven software engineering domain.
* [languageengineering.io](https://languageengineering.io) - A blog focused in language engineering with many examples implemented using MPS.
* [log verbose](https://blog.logv.ws/tag/mps/) - The repositor owner's own blog posts on MPS.
* [Official Website](https://www.jetbrains.com/mps/)
* [Programming Basics](https://markusvoelter.github.io/ProgrammingBasics/) - Uses MPS to teach the basics of programming to none computer science people.
* [Specific Languages](https://specificlanguages.com/) - Specific Languages blog: articles about practical MPS usage.
* [Strumenta](https://tomassetti.me/category/language-engineering/jetbrains-mps/) - Strumenta blog: articles about MPS and language engineering in general.

## [Research](#research)

### [Papers](#papers)

* [Classification Algorithms Framework (CAF) to Enable Intelligent Systems Using JetBrains MPS Domain-Specific Languages Environment](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8959196)
* [JetBrains MPS as Core DSL Technology for Developing Professional Digital Printers](https://link.springer.com/chapter/10.1007%2F978-3-030-73758-0_3)
* [Using Language Workbenches and Domain-Specific Languages for Safety-critical Software Development](http://www.voelter.de/data/pub/MPS-in-Safety-1.0.pdf)
* [The Design, Evolution and Use of KernelF](http://www.voelter.de/data/pub/kernelf-icmt.pdf) [Slides](http://www.voelter.de/data/presentations/icmt2018-kernelf.pdf)
* [Domain-Specific Languages for Efficient Satellite Control Software Development](http://mbeddr.com/files/dasia_wortmann.pdf)
* [Using C Language Extensions for Developing Embedded Software - A Case Study](http://mbeddr.com/files/mbeddr-cs-oopsla2015-preprint.pdf)
* [Automated Testing of DSLs Implementations: Experiences from Building mbeddr](http://mbeddr.com/files/sqj_2017.pdf)
* [Lessons Learned from Developing mbeddr - A Case Study in Language Engineering with MPS](http://mbeddr.com/files/sosym_2017.pdf)
* [Efficient Development of Consistent Projectional Editors using Grammar Cells](http://mbeddr.com/files/gc-sle.pdf)
* [IncA: A DSL for the Definition of Incremental Program Analyses](http://mbeddr.com/files/inca-ase.pdf)
* [An Extensible Framework for Variable-Precision Data-Flow Analyses in MPS](http://mbeddr.com/files/mps-df-ase.pdf)
* [Towards Usable Projectional Editors](http://mbeddr.com/files/projectionalEditing-sle2014.pdf)
* [Taming the Software Development Complexity with Domain Specific Languages](https://drive.google.com/file/d/1Vf2qKteV0XdisQk1sxqdEQMw4bejeoiW/view)

### Talks / Videos

* [GeeCON Prague 2017: why modern language workbenches matter](https://www.youtube.com/watch?v=FK4N4u9tlqw) - Talk by Vaclav Pech  about MPS.
* [ieeeComputerSociety episode 126](https://www.youtube.com/watch?v=MefWB5_BoHY) - Jetbrains MPS with Konstantin Solomatov
* [MPS Talk Series 2021](https://pages.jetbrains.com/mpstalkseries2021) - The MPS Talk Series was a free virtual event organized by JetBrains and itemis that took place in February 2021.
* [JetBrains MPS as a Tool for Extending Java](https://www.youtube.com/watch?v=7JTPogrzYwE)
* [JetBrains TV MPS Playlist](https://www.youtube.com/playlist?list=PLQ176FUIyIUYWfVn1BulLIJXILHUI8t9) - Official videos by JetBrains on MPS.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/coolya/mps.rocks/blob/master/CONTRIBUTING) ⭐ 67 | 🐛 4 | 🌐 Makefile | 📅 2025-12-12 first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-02._

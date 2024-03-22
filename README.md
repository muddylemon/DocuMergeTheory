# DocuMergeTheory

## Overview

DocuMergeTheory is an innovative project that intersects the rich field of textual criticism with modern technology, specifically focusing on the Hebrew Bible. By employing Git, a distributed version control system, DocuMergeTheory invites scholars, students, and enthusiasts to collaboratively explore, analyze, and interpret the textual variants and composition of the Hebrew Bible. This project is designed to harness Git's capabilities, such as branching, pull requests, and diffs, to facilitate a deep and nuanced understanding of the text's evolution over time.

## Objectives

- **Collaborative Textual Analysis**: Foster a collaborative environment where contributors can explore, annotate, and discuss textual variations of the Hebrew Bible.
- **Visual Comparison of Texts**: Utilize Git diffs to visually compare textual variants, enhancing understanding of the differences and their implications.
- **Educational Platform**: Serve as an educational tool for teaching the complexities of textual criticism and the history of the Hebrew Bible's composition.

## Key Features

- **Branching for Textual Traditions**: Create branches for each significant textual tradition within the Hebrew Bible, reflecting various sources and theories, such as those proposed by the Documentary Hypothesis.
- **Pull Requests for Scholarly Interpretation**: Use pull requests as a means for scholars to submit their interpretations, annotations, or corrections of the text, accompanied by detailed explanations and scholarly debate.
- **Diff for Comparative Analysis**: Leverage Git's diff tool to visually compare changes between branches, highlighting textual variations and facilitating in-depth analysis.


### Repository Structure

```
/DocuMergeTheory
    /texts
        /masoretic
            genesis.heb.txt
            exodus.heb.txt
            leviticus.heb.txt
            numbers.heb.txt
            deuteronomy.heb.txt
        /samaritan
            genesis.smr.txt
            exodus.smr.txt
            leviticus.smr.txt
            numbers.smr.txt
            deuteronomy.smr.txt
        /english
            /web
                genesis.en.txt
                exodus.en.txt
                leviticus.en.txt
                numbers.en.txt
                deuteronomy.en.txt
    /resources
        /fonts
            README.md
        /scripts
            README.md
            example_script.py
        /tools
            README.md
            tool_instructions.md
    /documentation
        README.md
        CONTRIBUTING.md
        LICENSE.md
    /vorlage
        /genesis
            genesis.en.txt
            genesis.heb.txt
        /exodus
            exodus.en.txt
            exodus.heb.txt
        /leviticus
            leviticus.en.txt
            leviticus.heb.txt
        /numbers
            numbers.en.txt
            numbers.heb.txt
        /deuteronomy
            deuteronomy.en.txt
            deuteronomy.heb.txt
```

### Directory Descriptions

- **/texts**: Contains the main textual traditions and translations. Each subdirectory (e.g., `/masoretic`, `/samaritan`, `/english`) holds files for the books of the Pentateuch in the respective tradition or translation. The naming convention (`[book].[lang].txt`) ensures clarity and ease of access.
    - **/masoretic**: For the Hebrew Masoretic Text.
    - **/samaritan**: For the Samaritan Pentateuch text.
    - **/english/web**: For the World English Bible translation, with potential to expand to other translations.

- **/resources**: A directory for supplementary materials that support the textual work, such as fonts for viewing and editing texts, scripts for processing or analyzing texts, and tools with instructions for use.
    - **/fonts**: Information and possibly links to download fonts suitable for viewing ancient scripts.
    - **/scripts**: Custom scripts for tasks like converting text formats, analyzing textual variants, etc.
    - **/tools**: Documentation and guides for tools used in textual analysis and repository management.

- **/documentation**: Essential documents for guiding contributors and users of the repository. This includes a general README, contributing guidelines (CONTRIBUTING.md), and licensing information (LICENSE.md).

- **/vorlage**: This directory mirrors the structure of `/texts` but is specifically for the foundational texts being used in the DocuMerge project, organized by book. It serves as a workspace for developing and discussing the base texts before they are considered part of the main textual tradition folders.



## Getting Started

### Prerequisites

- Installation of Git on your computer.
- A foundational knowledge of Git operations.
- Interest or background in the Hebrew Bible and textual criticism.

### Installation

1. **Clone the Repository:**

```bash
git clone https://github.com/muddylemon/DocuMergeTheory.git
cd DocuMergeTheory
```

2. **Explore and Participate:**

Explore the branches to find the textual traditions you are interested in. Engage with the project by creating your own branches for specific readings or interpretations, or by commenting on and reviewing pull requests.

### Contribution Guidelines

- **Branch Creation**: Create new branches for specific textual readings or when introducing significant scholarly interpretations.
- **Creating Pull Requests**: When you propose a change or add a new interpretation, create a pull request. Include detailed explanations of your contributions, supported by scholarly research.
- **Using Git Diffs**: Utilize Git diffs for comparing textual variations across branches. This can serve as a basis for scholarly discussion and further analysis in pull requests.

## Collaborative Process

1. **Branch for New Interpretations**: When studying a particular textual variant, start by creating a new branch from the relevant traditional text branch.
2. **Annotate Using Commit Messages**: Use commit messages to provide detailed annotations about the textual changes or variants you are introducing.
3. **Submit Pull Requests**: Create a pull request to merge your findings into the main branch of the textual tradition. Use this opportunity to detail your scholarly interpretation and invite discussion.
4. **Engage in Scholarly Debate**: Participate in discussions on pull requests, offering insights, critiques, and further interpretations based on your expertise and research.

## Educational Use

DocuMergeTheory offers a unique platform for educators and students to engage with the text of the Hebrew Bible in a dynamic and interactive manner. It can be integrated into courses on biblical studies, ancient history, and religious studies as a tool for teaching textual criticism and the historical development of religious texts.

## Support

For support or to engage with the DocuMergeTheory community, please visit our [GitHub issues page](https://github.com/muddylemon/DocuMergeTheory/issues) or contact the project maintainers directly via email.

## License

DocuMergeTheory is licensed under the MIT License. See the LICENSE file in the repository for more details.

## Acknowledgments

- Our deepest gratitude to the scholars, students, and enthusiasts whose contributions enrich this project.
- Special thanks to the broader academic and open-source communities for their inspiration and support in creating this platform.

DocuMergeTheory represents a pioneering step in the fusion of ancient textual scholarship with contemporary technology, offering new pathways for exploration, education, and collaboration.

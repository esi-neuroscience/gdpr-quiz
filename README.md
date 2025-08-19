<!--
Copyright (c) 2025 Ernst Strüngmann Institute (ESI) for Neuroscience in Cooperation 
with Max Planck Society and Max Planck Institute for Human Development (MPIB)

SPDX-License-Identifier: CC-BY-SA-4.0
-->

# gdpr-quiz
A short interactive quiz covering what you really need to know about data 
protection for human subject research

## Setup

The quiz is built with [Quarto](https://quarto.org/) version 1.6+ using the 
[Quizdown Extension](https://github.com/parmsam/quarto-quizdown). Use the 
accompanying conda environment file to reproducibly build the html site: 


```shell
conda env create -f conda_env.yml
conda activate gdpr-quiz
quarto render
```

For working on the website use Quarto's `preview` mode:

``` shell
quarto preview
```

More information can be found in the [Quarto docs](https://quarto.org/docs/websites/index.html#workflow). 

## Contributing

Contributions to are always welcome! You can 
[open an issue](https://github.com/esi-neuroscience/gdpr-quiz/issues/new)
and propose changes/additions. Alternatively, feel free to 
[fork this repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo), 
and open a [pull request](https://github.com/esi-neuroscience/gdpr-quiz/pulls). 

## Support

For general questions related to Quarto, please visit the (excellent) 
[online documentation](https://quarto.org/docs/presentations/).

If you have questions pertaining to the quiz specifically, please use our 
[GitHub Issue Tracker](https://github.com/esi-neuroscience/gdpr-quiz/issues)

## Authors and Acknowledgment

The quiz is based on a data protection course initially developed by 
[Tobias Bengfort](https://github.com/xi). The current version of the interactive 
quiz was designed by [Stefan Fürtinger](https://github.com/pantaray). 

## License

This project is licensed under the terms of the Creative Commons Public Licenses 
(see [LICENSES](./LICENSES) for details). 

## Project status

This project is actively maintained and (sometimes) updated.

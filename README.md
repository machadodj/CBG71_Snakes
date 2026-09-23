# CBG71_Snakes

Poster for the 71st Brazilian Congress of Genetics (Genética 2026), held in Florianópolis, Santa Catarina, Brazil, from September 29 to October 2, 2026.

**Evolution of the repeatome and satellitome in three endangered insular species of the genus *Bothrops* (Squamata: Serpentes: Viperidae)**

Igor Salles de Oliveira, Giselle Pessanha Pessoa, Giovanna Yumi Scorsim Omura, Denis Jacob Machado, Milton Yutaka Nishiyama Junior, and Maria José de Jesus Silva

Igor Salles de Oliveira presents the poster on September 30, 2026, from 17:00 to 19:00 (Trabalho #244, thematic area Genética Evolutiva).

## Accepted abstract

Cite the abstract accepted by the congress as follows. The congress lists it among the approved works at https://genetica2026.com.br/aprovados, and its text will appear in the electronic proceedings of the event.

> Salles de Oliveira, I., Pessoa, G. P., Omura, G. Y. S., Jacob Machado, D., Nishiyama Junior, M. Y., and Silva, M. J. J. 2026. Evolution of the repeatome and satellitome in three endangered insular species of the genus *Bothrops* (Squamata: Serpentes: Viperidae). Abstract, Trabalho #244. 71º Congresso Brasileiro de Genética (Genética 2026), Sociedade Brasileira de Genética, Florianópolis, SC, Brazil, September 29 to October 2, 2026.

The congress does not allow changes after submission. The poster and `ABSTRACT.md` update that text with the best information available to the authors, following the manuscript on the four genomes. The main changes are the repeat content (48.6 to 50.0% of each genome), the TE superfamilies with renewed recent activity, and the satellite DNA counts, which the poster reports as families (1,720) and homology groups (1,347).

## Contents

| File | Content |
|---|---|
| `Poster_CBG71_Snakes.pdf` | The poster, 100 cm by 100 cm |
| `ABSTRACT.md` | An updated abstract that matches the poster |
| `main.tex` | LaTeX source of the poster |
| `latexmkrc` | Sets LuaLaTeX as the compiler |
| `figures/` | Photos for Figure 1 and Figures 2 to 7 |
| `logos/` | Logos of the event, the host institutions, and the funders |
| `LICENSE` | Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International |

## Building the poster

The repository is linked to an Overleaf project. In Overleaf, the `latexmkrc` file selects LuaLaTeX. To build it locally with TeX Live, run:

```sh
latexmk -lualatex main.tex
```

The poster uses the TeX Gyre Heros font and the `fontawesome5` package, both included in TeX Live. Each poster column has a fixed height. If an edit makes a column run past that height, the build log reports it as `Overfull \vbox`.

## License

Our text and figures are available under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license (CC BY-NC-SA 4.0). See `LICENSE`.

The license does not cover material owned by others. The logos belong to their organizations. The photographs in Figure 1 keep their own terms: *Bothrops alcatraz* by Otavio A. Marques, licensed under CC BY 4.0 (https://commons.wikimedia.org/wiki/File:Bohtrops_alcatraz_OAVM14.jpg); *B. insularis* by Igor Salles-Oliveira; and *B. sazimai* by Ricardo Sawaya. Figure 2 was created in BioRender (BioRender.com) and follows the BioRender terms of use.

## Contact

Igor Salles de Oliveira, igor.oliveira.esib@esib.butantan.gov.br

Denis Jacob Machado, dmachado@charlotte.edu

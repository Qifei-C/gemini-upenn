# Unofficial Poster Template for University of Pennsylvania
 
A fork of Gemini.  The theme for this poster template is inspired by the University of Pennsylvania’s official [logos and branding guidelines](https://branding.web-resources.upenn.edu/logos-and-branding). It incorporates the colors, typography, and visual style outlined in the Penn Branding Guidelines. The design is tailored to ensure alignment with Penn’s visual identity, making it suitable for use in official or academic settings associated with the university.


![Poster_Template_for_UPenn-1](https://github.com/user-attachments/assets/dbf831a7-6094-4133-ace4-549ebc942d61)


## Dependencies

* A TeX installation that includes [LuaTeX]
    * You also need `latexmk` if you want to use the provided `Makefile`
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato], which are both available under Open Font License

## Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

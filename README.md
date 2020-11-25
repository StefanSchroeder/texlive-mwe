# texlive-mwe
A collection of minimal-working-examples for various texlive-packages.

# Goal

The goal of this project is to produce many "minimal-working-examples" as explained by
https://tex.meta.stackexchange.com/questions/228/ive-just-been-asked-to-write-a-minimal-working-example-mwe-what-is-that

One of the problems with LaTeX-packages on CTAN/TeXLive is that you first need to browse through the 
sometimes non-optimal documentation of the package just to find that there is no MWE in there.

This project wants to help out.

Ultimately, it is used as an experimentation lab to examine package dependencies which are
not explicitly stated for many packages.

As a consequence, it is NOT the intention to show off the features or capabilities of a particular package.
We just want to make it compile.

# What to expect

1. Every folder has the name of a package.
2. Every folder has one file *mwe.tex* that uses that package.
3. There may be more MWE which will be named, mwe-2.tex, mwe-3.tex, etc.

# Resources

This work is inspired by Nixos's lack of dependency resolution for TexLive packages. 
This list was used to determine the list of packages:

https://raw.githubusercontent.com/NixOS/nixpkgs/master/pkgs/tools/typesetting/tex/texlive/pkgs.nix


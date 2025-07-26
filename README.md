# THINK eLearn

⚠️ Our website was transitioned to a Wagtail-powered CMS in July 2025. This code is no longer being maintained.

This is the source code for THINK eLearn's website. It is built using [Jekyll](https://jekyllrb.com/), a static site generator.

Build the site and make it available on a local server.

    bundle exec jekyll serve

Browse to <http://localhost:4000>

Pass the `--livereload option` to serve to automatically refresh the page with each change you make to the source files:

    bundle exec jekyll serve --livereload

## Overriding theme defaults

<https://jekyllrb.com/docs/themes/#overriding-theme-defaults>

To locate a theme’s files on your computer:

Run bundle info --path followed by the name of the theme’s gem, e.g., bundle info --path minima for Jekyll’s default theme.

Open the theme’s directory in Finder or Explorer:

    # On MacOS
    open $(bundle info --path minima)

    # On Windows
    # First get the gem's installation path:
    #
    #   bundle info --path minima
    #   => C:/Ruby26-x64/lib/ruby/gems/3.1.3/gems/minima-2.5.1
    #
    # then invoke explorer with above path, substituting `/` with `\`
    explorer C:\Ruby26-x64\lib\ruby\gems\3.1.3\gems\minima-2.5.1

    # On Linux
    xdg-open $(bundle info --path minima)

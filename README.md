Signal Email Templates
========================

Signal includes email templates ready for use. This repo has all the source files for those templates.

Templates follow a standard directory structure.

    root/
      template.html       # The HTML document this template defines
      resources/          # A directory containing all assets needed for this template
      library_images.yml  # YAML file that denotes which resources should be available to choose in an editable image
      layouts/            # Directory containing repeatable layout types
        image_left.html   # A layout definition named image_left
        image_left.png    # The icon for image_left, used in the email editor
        ...
      styles.yml          # Custom WYSIWYG styles available when using this template

Note that only the template.html file is required for a template, the rest of the files take advantage of Signal templating capabilities.

To read more about building email templates in Signal, check out http://support.signalhq.com/kb_article/build-email-templates/.

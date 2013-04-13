# Signal email templates

Signal includes email templates ready for use. This repo has all the source files for those templates.

## Directory structure, required files and assets

Templates follow a standard directory structure:

    root/
      template.html       # The HTML document this template defines
      resources/          # A directory containing all assets needed for this template

Only the template.html file is required for a new template.

If you wish to take advantage of more advanced templating features like repeatable content regions, you would see a directory structure more like this:

    root/
      template.html       # The HTML document this template defines
      resources/          # A directory containing all assets needed for this template
      library_images.yml  # YAML file that denotes which resources should be available to choose in an editable image
      layouts/            # Directory containing repeatable layout types
        image_left.html   # A layout definition named image_left
        image_left.png    # The icon for image_left, used in the email editor
        ...
      styles.yml          # Custom WYSIWYG styles available when using this template

To find out more, read our [guide to building email templates](http://www.signalhq.com/resources/guides/building-email-templates-in-signal/).

## Copyright and license

Copyright 2013 Signal

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

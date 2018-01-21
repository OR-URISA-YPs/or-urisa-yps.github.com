# Oregon URISA Young Professionals

This is the source for the [OR-URISA YP website](http://orurisayp.org/).

## To create a new blog post

1. [Fork](https://help.github.com/articles/fork-a-repo/) this repository.
2. In your fork, go to the `_posts` directory.
3. Create a new file.

    ⚠️ **How you name files in this folder is important.**
    
    Jekyll requires blog post files to be named according to the following format:
    
    `YEAR-MONTH-DAY-lower-case-with-dashes-for-spaces.md`

    Here's example:

    `2013-04-16-neat-and-free-geodata-conversion-tools.md`
    
    I strongly recommend keeping all letters lowercase, as this will end up being the URL of the post. For example, the above post's filename would result in a post being available at the following address:
    
    `http://orurisayp.org/posts/2013/04/16/neat-and-free-geodata-conversion-tools`

4. Write a new blog post using the Github editor! You'll need a little metadata at the top:

    ```md
    ---
    layout: post
    title: The Title of your Blog
    ---
    ```

    Once you've filled that out, you can write the article itself using [Markdown](https://guides.github.com/features/mastering-markdown/). Here's some example content:

    ```md
    # Blog Title

    This is a paragraph!

    - this
    - is
    - a
    - list

    [Here's a link](http://orurisayp.org/).

    ![This is a picture](http://orurisayp.org/assets/images/orurisalogo.png)
    ```

5. Make sure to commit your changes when you're done by filling out the **Commit changes** section at the bottom of the page and clicking the big green button.

    If you're comfortable working with Ruby and the command line, you can try previewing the site locally by following the [installation](#Installation) instructions below and starting the Jekyll server locally.

6. When you're happy with your post, open a pull request to merge your changes into the main repository.
7. An admin for the OR-URISA YP github organization will review your pull request and merge it if everything looks okay. Hooray! :tada:

## Running the site locally

This is only necessary if you want to see a preview of the site with your changes on your own computer before publishing.

This is a [github pages](https://pages.github.com/) site using [Jekyll](https://jekyllrb.com/).

To run this site locally you'll need to be comfortable working from a terminal application like `Terminal` on Mac or `Command Prompt` on Windows.

You'll also need to have both [Ruby](https://www.ruby-lang.org/en/) and Jekyll installed to get it working on your local machine.

To install Ruby, follow instructions from the [Ruby installation guide](https://www.ruby-lang.org/en/documentation/installation/).

Once that's done, you can install Jekyll with the following command:

```
gem install jekyll
```

Once you've successfully installed Ruby and Jekyll, there's only a few more steps left.

1. Fork this repository
2. Clone your fork to your computer

```
git clone git@github.com:{YOUR USERNAME}/or-urisa-yps.github.com.git
```

3. `cd` into the repository you just cloned
4. Start a local server with the following command:

```
jekyll serve
```

## Notes

Built with Jekyll-Bootstrap: <http://jekyllbootstrap.com>, which is licensed with [Creative Commons](http://creativecommons.org/licenses/by-nc-sa/3.0/)

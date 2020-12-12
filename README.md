# club-website-template

This is an easily customizable template for club websites. Here is a [website built using this template.]()

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "club-website-template"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: club-website-template
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install club-website-template

## Usage

This theme has got 5 layouts and 3 includes.

### Available layouts

**Move to the markdown files as mentioned in the description of each layout below for further instructions on customization. You don't need to change any of the layout files. Just change their markdown files.**
1. indexLayout.html &larr; It is the front page your website. The name of your club, its logo and the links to other pages can be customized in _config.yml while the background and fonts can be changed in the front matter of home.md. For customizing the social links, see the includes section.
3. homeLayout.html &larr; It is the home page of your website. All the customization for this page except the header and footer can be made in the front matter of home.md
4. eventsLayout.html &larr; It is used by all the events. The font and background can be customized in _config.yml. A sample markdown file for an example event is provided in _events/Example. It contains further details.
5. pastEventsLayout.html &larr; It's the archive of all the events conducted by your club. It can be customized in the front matter of pastEvents.md. It automatically lists your posts from the _events  folder. You can have subfolders in _events for organization purposes. It won't have any effect on the code.
6. peopleLayout.html &larr; It lists the names and a photograph of each convenor/co-convenor/anyone who has held any role in the past. It can be customised in the front matter of people.md. In order to add the names of more people, head to _data/people.yml

### Include
1. header.html &larr; It's the header which appears on every page of your website except the front page. It's font and background can be customised in _config.yml
2. footer.html &larr; It's the footer which appears on every page of your website except the front page. It's font and background can be customised in _config.yml. The social media links are included from socialLinks.html
3. socialLinks.html &larr; It contains the links to various social media/github pages of your club. It's included by the footer to display the links. You can add/remove/update these links in ```_data/social.yml```

### Assets
1. Some of the clubs don't have a logo. So, we have provided ```/assets/img/logo.png``` which is a transparent image. You can use it or provide a logo for your club. This logo will appear above the club name on the front page.
2. Icons for several social media sites have been provided in ```/assets/img/social/``` for use in socialLinks.html

So, all in all, you have to edit the following files
1. ```_config.yml```
2. ```index.md```
3. ```home.md```
4. ```pastEvents.md```
5. ```people.md```
6. ```_data/social.yml```
7. ```people.yml```
8. Provide all images you are gonna use.

**Need help?**
Contact [me.](mailto:ms19117@iisermohali.ac.in)

**Need help with hosting?**
Contact [me](mailto:ms19117@iisermohali.ac.in) or the convenor of Turing Club. You can host your website on Github Pages using the github account of your club or you can host it at [IISERM](https://iiserm.github.io).

## Contributing

Bug reports are welcome on GitHub at https://github.com/James471/club-website-template/issues. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

Please discuss any changes before sending pull requests. I can be found somewhere in the library or at my [email address.](mailto:ms19117@iisermohali.ac.in) Or, you can always fork this repo, customize it the way you want and use it for your website. I will be glad to help if I can.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `club-website-template.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).


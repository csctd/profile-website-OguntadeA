# Ayishat Oguntade Profile Website

Welcome to my website, peers, professors, and companies   
<!-- enter your target audience after the comma above -->

Since you're here, you might be: 
- Emma; a top employee from a  tech job trying to get a better understanding of who I am to consider hiring me.
- Jhon; a friend who is looking at my website and giving me feedback on if he can see my website well with his sight imparemnet.
- Nikki; a student/peer looking at my work to see if she would want to work with me in the future and get to know me.
<!-- make a bulleted list of 3 fictional visitors to your site. Include a few detials about them that could impact how you design for them. For each visitor, assign a task or goal they have for visiting your profile website -->

[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=11521495)
# Sphinx Profile Page

This is is a template for a resume/ personal portfolio, built with Sphinx! Based on [Chris Holdgraf's personal site](https://github.com/choldgraf/choldgraf.github.io)

This template is designed for use in the URI CS TD SSP. 


## Tips for Updating the Content of this site

- sidebar variables are defined in `info-.yml` 
- sidebar formatting for sidebar is in `_templates/hello.html` 
- variables are used via `html_context`
- get social links back by removing setting to `navbar_end` in `conf.py` and set values by [example](https://github.com/choldgraf/choldgraf.github.io/blob/main/conf.py#L41)


## To work with this repo offline (or in codespaces)

**This requires having python installed then installs a package that helps build the website**

The easiest way to build the website is to use `nox`, which handles all of the environment generation automatically.
To do so, follow these steps:

1. Install `nox`.

   ```shell
   pip install -U nox
   ```
2. To run a live webserver that will auto-build and reload when you make changes, run:

```shell
nox -s docs-live
```

If on Codespaces, use accept the port forwarding and open the forwarded port in a new browser tab to preview your site while you work. 

<!-- 
Run `nox`

   ```shell
   nox -s docs
   ```

this should install a Sphinx environment and build the site, putting the output files in `_build/html`. -->

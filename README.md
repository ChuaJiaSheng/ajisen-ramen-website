# Ajisen Ramen Restaurant Website

A multi-page restaurant website created as HTML/CSS coursework. The pages present restaurant information, food menus, promotions, and form layouts for a typical restaurant customer journey.

**Stack:** HTML · CSS · static image assets

![Restaurant banner](images/Banner_Ajisen_Remen.jpg)

## Pages

| Page | Content |
| --- | --- |
| [index.html](index.html) | Homepage and promotions |
| [aboutUs.html](aboutUs.html) | Restaurant information |
| [menu.html](menu.html) | Food menu presentation |
| [order.html](order.html) | Ordering interface |
| [contactUs.html](contactUs.html) | Contact-page layout and form |
| [recruitment.html](recruitment.html) | Recruitment information/form |
| [login.html](login.html), [register.html](register.html) | Account-form layouts |

## Reproduce locally

**Prerequisites:** Git, Python 3, and a web browser. No backend, API credentials, or package installation is required.

```sh
git clone https://github.com/ChuaJiaSheng/ajisen-ramen-website.git
cd ajisen-ramen-website
python -m http.server 8000
```

If your system uses `python3`, substitute it for `python`. Open `http://localhost:8000/index.html` in a browser.

**Expected result:** the restaurant homepage renders with its banner, styles, and navigation. Open the menu and another page through the navigation; their images and styles should also load. This reproduces the static interface, not order processing or account authentication.

Stop the server with Ctrl+C. If port 8000 is occupied, use `python -m http.server 8001` and open port 8001 instead. If the browser shows a directory listing or missing files, make sure the terminal is in the cloned repository root. Preserve the filenames, including spaces and capital letters, when editing asset paths.

## Folder guide

- Root `*.html` files contain the individual pages.
- [css/](css/) contains page stylesheets. Some filenames contain spaces; preserve their exact spelling when changing links.
- [images/](images/) contains the supplied restaurant and menu assets.

## Scope

The repository provides frontend pages. Their presence does not establish functioning customer accounts, saved orders, payments, recruitment submissions, or a contact-message delivery service. Do not enter real personal or payment details into the demonstration forms.

Restaurant branding and images are retained as part of the historical coursework. This is a student portfolio project, not a claim of affiliation with or an official website for Ajisen Ramen. Menu details and promotions should be treated as historical content.

## Author

Chua Jia Sheng.

# my_developer_tools
Разные полезности

/* :root {
  --main-font: "Roboto", sans-serif;
  --secondary-font: "Raleway", sans-serif;
  --accent-color: #2196f3;
  --main-color: #212121;
  --black-color: #000000;
  --white-color: #ffffff;
  --content-description: #757575;
  --background: #f5f4fa;
  --background-btn-hover: #188ce8;
  --background-section: #2f303a;
  --text-color-default: rgba(255, 255, 255, 0.6);
  --second-title-mb: 50px;
  --filters-btn-pd: 6px 22px;
  --section-pt: 94px;
  --section-pb: 94px;
  --link-padding-tp: 32px;
  --link-padding-bt: 32px;
  --color-icon-clients: #afb1b8;
  --transition-time-cubic: 250ms cubic-bezier(0.4, 0, 0.2, 1);
  --transition-time-cubic-modal: 500ms cubic-bezier(0.4, 0, 0.2, 1);
} */

body {
  font-family: var(--main-font);
  color: var(--main-color);
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin: 0;
}

ul,
ol {
  margin: 0;
  padding: 0;
}

img {
  display: block;
}

.link {
  text-decoration: none;
}

.list {
  list-style: none;
}

.address {
  font-style: normal;
}

.visually-hidden {
  position: absolute !important;
  clip: rect(1px 1px 1px 1px); /* IE6, IE7 */
  clip: rect(1px, 1px, 1px, 1px);
  padding: 0 !important;
  border: 0 !important;
  height: 1px !important;
  width: 1px !important;
  overflow: hidden;
}

.container {
  width: 1200px;
  margin: 0 auto;
  padding-left: 15px;
  padding-right: 15px;
}

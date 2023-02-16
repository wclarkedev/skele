# Skeleton

Skeleton is a framework for easily creating common web page components such as navigation bars, grid layouts and forms. 

Skeleton will:
- be fully responsive 
- contain both JavaScript and CSS code to make the components look nice and work on all devices
- be written in SCSS and JavaScript
- have *optional* default styles
- have informative documentation 
- include specific preset style options for different elements on website
- have a full range of options that work well together for grids, navigation bars and footers. 

Preset components: 
- Feature grids
- Profile grids
- Testimonial banners
- Navigation & Footer

Default styled elements: 
- Tables
- Headings & Paragraphs
- Fonts
- Forms
- Lists

Classes:
- Apply default styles: `.skele:default`
- Apply specific default style: (Apply `=`, Remove `-`)
  - Tables `.skele:default=tbl`
  - Text `.skele:default=text`
  - Headings `.skele:default=h`
  - Paragraphs `.skele:default=p`
  - Fonts `.skele:default=ff`
  - Forms `.skele>default=form`
  - Lists `.skele>default=list`
- Preset styles `.skele:preset>`
  - Preset footer `.skele:preset>footer`
  - Preset nav `.skele:preset>navigation`
  - Preset sidebar `.skele:preset>sidebar`
  - Preset testimonial `.skele:preset>testimonial`
  - Preset feature grid `.skele:preset>feature-grid`
  - Preset profile grid `.skele:preset>profile-grid`

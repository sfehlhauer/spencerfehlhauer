# spencerfehlhauer
baseUrl: /
languageCode: en-us
theme: hello-friend
copyright: ''
paginate: 5

params:
  # dir name of your blog content (default is `content/posts`)
  contentTypeName: posts
  # "dark" or "light"
  defaultTheme: dark
  # if you set this to 0, only submenu trigger will be visible
  showMenuItems: 2

languages:
  en:
    title: Your site title
    subtitle: Your site subtitle
    keywords: ''
    menuMore: Show more
    writtenBy: Written by
    readMore: Read more
    readOtherPosts: Read other posts
    newerPosts: Newer posts
    olderPosts: Older posts
    dateFormatSingle: 2006-01-02
    dateFormatList: 2006-01-02
    
    params:
      logo:
        logoText: hello friend
        logoHomeLink: /
    #   or
    #
    #   path: /img/your-example-logo.svg
    #   alt: Your example logo alt text
    
    menu:
      main:
      - identifier: about
        name: About
        url: /about
        weight: 1000
      - identifier: showcase
        name: Showcase
        url: /showcase
        weight: 500
      - identifier: daily_quotes
        name: Daily Quotes
        url: /dailyquotes
        weight: 400

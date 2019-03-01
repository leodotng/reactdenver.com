# React Denver Website

## Getting Up and Running

1. `git clone git@github.com:reactdenver/react-denver-v2.git`
2. `npm install` _need help getting node setup? [checkout this video](https://www.youtube.com/watch?v=K5_B737B9l0) from [@stolinski](https://github.com/stolinski)_
3. `npm start`
4. help us out!

## About

- reactdenver.com is built using [GatsbyJS](https://gatsbyjs.org), an amazing static site generator using React.
- Pages are created with markdown files in `src/pages/markdown`. To add a page, copy one of the existing pages and edit the file.
  - pages use templates defined in `src/templates`
- Meetup events are pulled in from meetup.com's API.
  - to see meetup events locally, you'll need to [grab an API key from Meetup.com](https://secure.meetup.com/meetup_api/key/) and set it in your `.env` file

## Deployments

The site automatically deploys when commits are made or merged to the master branch.
Pull requests automatically build preview URLs via netlify.

## Contributing

See something you can help with? Something that needs work? If you have time, we'd greatly appreciate pull requests for updates!
If you notice something and need help implementing, please file an issue and someone will look into it.

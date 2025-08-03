# Return2Play API Documentation

This repository contains the documentation for the Return2Play API, which provides injury prediction and player status data for sports applications.

## Features

- **Player Status API**: Get real-time injury status and predictions for individual players
- **All Players API**: Retrieve comprehensive data for all players in our database
- **Player Statuses API**: Get injury status for multiple players in a single request
- **Health Check API**: Verify API status and connectivity

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## API Documentation

The documentation includes:

- **API Reference**: Complete endpoint documentation
- **Code Examples**: Integration examples for JavaScript, Python, React, and more
- **Data Models**: Response structure documentation
- **Use Cases**: Fantasy sports, sports betting, and sports news applications

## Need help?

### Support

- **Email**: [support@return2play.com](mailto:support@return2play.com)
- **Documentation**: [https://docs.return2play.com](https://docs.return2play.com)

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)

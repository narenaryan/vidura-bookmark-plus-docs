# User Permissions Disclosure

We repect Chrome API best practices and our installed users can find permissions disclosure here:

The current extension needs below permissions to function as promised to the user:

| Manifest API Permission | Reason |
--------------------------|---------|
| storage | for storing client ID and bookmark knowledge graph data |
| bookmarks | for creating bookmark folders based on topics |
| scripting | to extract meta information of bookmarked page for classification into topics and sub-topics |
| contextMenus | to simplify user experience while bookmarking with extension |
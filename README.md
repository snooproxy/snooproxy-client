# Snooproxy Pro   

**We *do not* endorse piracy of any kind. We simply enjoy programming and large user counts.**

## Links And Resources
| Service                            | Link                                                                                        | Source Code                                                   |
|------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| Snooproxy Self Hosting Guide       | [snooproxy-docs](https://docs.snooproxy.com)                                                | [source code](https://github.com/snooproxy/self-hosting)      |
| Extension                          | Work in Progress                                                                            |                                                               |
| Proxy                              | [snooproxy-proxy](https://proxy.snooproxy.com)                                              | [source code](https://github.com/snooproxy/snooproxy-proxy)   |             
| Backend                            | [sudo-flix's backend](https://backend.sudo-flix.lol) (Our own Backend is in Development)    | Closed Source (of course, ours will be public)                |
| Frontend (Client)                  | [snooproxy-client (sɴᴏᴏᴘʀᴏxʏ ᴘʀᴏ)](https://snooproxy.com)                                   | [source code](https://github.com/snooproxy/snooproxy-client)  |
| Providers                          | [snooproxy-providers](https://snooproxy.com)                                                | [source code](https://github.com/snooproxy/providers)         |

***We provide these if you are not able to host yourself, though We do encourage hosting the frontend.***


## Referrers
- [Piracy Subreddit Megathread](https://www.reddit.com/r/Piracy/s/iymSloEpXn)
- [Toon's Instances](https://erynith.github.io/movie-web-instances)
- Search Engines: DuckDuckGo, Bing, Google
- Rentry.co


## Running Locally
Type the following commands into your terminal / command line to run Snooproxy locally
```bash
git clone https://github.com/snooproxy/snooproxy-client.git snprxy
cd snprxy
git pull
pnpm install
pnpm run dev
```
Then you can visit the local instance [here](http://localhost:5173) or, at local host on port 5173.


## Updating a Snooproxy Instance
To update a Snooproxy instance you can type the below commands into a terminal at the root of your project.
```bash
git remote add upstream https://github.com/snooproxy/snooproxy-client.git
git fetch upstream # Grab the contents of the new remote source
git checkout <YOUR_MAIN_BRANCH>  # Most likely this would be `origin/main`
git merge upstream/main
# * Fix any conflicts present during merge *
git add .  # Add all changes made during merge and conflict fixing
git commit -m "Update Snooproxy instance (merge upstream/main)"
git push  # Push to YOUR repository
```


## Contact Us
**Email:** *[hello@snooproxy.com](mailto:hello@snooproxy.com)*


# FLYToken (FLY)

## Abstract
Following document will report a detailed description about the flytalia.com native token FLYToken (FLY).
FLYToken is a ERC20 Token deployed on Ethereum network.
Hereby the main characteristics:
* Initial supply = 1.000.000 FLYs
* Cap = 3.200.000 FLYs
* Mintable
* Burnable 
* ERC20 compliant (approve issue solved with allowance)
* Circulating supply visible


## Intro
### Why an ERC20 Token for Flytalia

The reason I decided to deploy such a token is simple. To reward users who decide to share their photos and mostly the location where they took the shoot.
Rewarding by fiat currency would have been an option, but not the best one in my opinion. 
For many reasons I won't be listing here. If you are interested of course we can have a discussion.

Therefore, since we are living the blockchain technology era, I decided to create FLYTokens.

Users who share photos on this platform are passionate about looking for hidden beautiful places in order to shoot an amazing photo. By means on FLYTokens they will be able to get more of these amazing shoots, taken by other users whith which they share the same passion.

### How has been set Initial supply, Cap and Distribution

Since I wanted to have a cheap contract to deploy on Ethereum, I tried to keep the code as simple as possible, still being ERC20 compliant and eventually tradable in future.
Token cap has been set considering an average of 8000 hurban centers in Italy, and assuming that ideally there would be 10 photos for each one. 
I know it's not a lot but this is a kind of stimulus to really find the best places around.
Ideally photos will be with 4k resolution (4096x2160).

For the moment the distribution criteria is very basic and probably full of issues. In the future I will try to come up with something more sophisticated but for the moment FLYs will be tested on mainnet as they are.
I decided to distribute FLYs depending on the photo resolution.
Basically users will get as many FLYs as the figures of the resolution of the photo they provide, first 2 digits excluded (below some examples)
- 500×480 : 5 FLYs
- 720×480 : 7 FLYs
- 1280×720 : 12 FLYs
- 1920×1080 : 19 FLYs
- 2048×1080 : 20 FLYs
- 4096×2160 : 40 FLYs

Considered what said above then, it is clear how I fixed the cap (8000 x 10 x 40).
Initial supply instead has been selected considering the amount of photos I am currently processing and their resolution.

### How can FLYs be used

For the moment, basically FLYs can be used just to get high quality photos from this platform.
Users can still decide to pay for photos with fiat. But they will be given the chance to use FLYs too.
Low resolution preview of the photos and their location instead is free and available on "Discover" page at flytalia.com.

When requestion high quality photos, currently users will need to request a quotation to myself.
I am working in implementing this exchange through smart contract in order to make transactions more efficient and safe.

At the moment anyway everything is work in progress so I will keep it the old way.

Later one I am planning to list FLYs on Uniswap by providing liquidity with the income of this platform.
So if you want to support this, your tips will be welcome. Remember flytalia.com is Brave verified and you can tip some BATs if you are using Brave Browser.

### Why did I create FLYs and FLYtalia

Mostly I did it for fun, in order to create a full project from the idea, to a live website/platform managed through smart contracts on Ethereum.
Also it is a way to make people find out places they didn't even imagine they could exist in my country.
So if you are planning your next trip and you have no idea where to start from, let your eyes decide for you. Visit flytalia.com and choose.

And don't forget to share your photos once you are back and get rewarded with FLYs!

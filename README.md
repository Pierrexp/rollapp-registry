# RollApp registry

![RR](https://github.com/dymensionxyz/rollapp-registry/assets/109034310/31dada06-064d-41bc-854c-9181054bf7aa)

A registry for RollApps on Froopyland testnet:

This repository is dedicated to the listing process of RollApps on the [Portal](https://portal.dymension.xyz/rollapps). Please follow the instructions for listing a RollApp:

1. Make sure to have successfully deployed and are running a RollApp instance. All outputs on `Roller Run` screen should show the RollApp running in `active` state.
2. IBC connections take up to thirty minutes to establish a connection with the Dymension Hub. Test the IBC connection by submitted a IBC transfer to the Dymension Hub faucet following the documentation listed [here](https://docs.dymension.xyz/build/quick-start/roller-quick/ibc-transfer).
3. Clone this repo using:

```bash
git clone https://github.com/<your-github-username>/rollapp-registry
```

4. Create a new folder with the following structure:

```tree
├── <RollApp-ID>
│   ├── <RollApp-ID>.json
│   └── logos
│       └── <RollApp-ID>-logo.svg
```

5. Export the RollApps configuration JSON file by running `roller config export`. This will return a file that you will open a PR in this repository with. Add this information to the `<RollApp-ID>.json` file created.

6. Add your RollApp logo in the `logos` folder. This can be SVG, PNG, or JPG format. Please keep the size of the file to a minimal.

7. Create a PR to https://github.com/dymensionXYZ/rollapp-registry

    For a demonstration of a step-by-step guide to creating a PR please follow the [GitHub documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) or watch this helpful [youtube video](https://www.youtube.com/watch?v=a_FLqX3vGR4).

8. Pair the RollApp on the Discord channel: [here](https://discord.com/channels/956961633165529098/1140590139022782474) by entering `$pair <RollApp-ID>` (replace <RollApp-ID> with your customized RollApp ID).

A community moderator will then begin a conversation with you in Discord. Please follow attentively to get the listing process fulfilled quickly. If you have any question please feel free to reach out to the coreteam and community on Discord. We're here for you!

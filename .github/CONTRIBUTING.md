~ contributing to nichroma
> read [code of conduct](./CODE_OF_CONDUCT.md) before submitting.

~ contribution workflow
1. fork & branch: fork the repository and create a feature branch.
2. commit: keep every text or conversation lowercase on github please.
3. open your pr: keep it focused and small with clear summaries.
4. include visuals: add screenshots or videos.

~ development
1. clone repo
    ```
    git clone https://github.com/luanderfarias/nichroma
    ```
2. unzip and cd to main
3. install neu
    ```
    npm install -g @neutralinojs/neu
    ```
    > you might encounter errors while running cli commands on powershell, if that happens please refer to the [neutralinojs documentation](https://neutralino.js.org/docs/getting-started/your-first-neutralinojs-app)
4. Run
    ```
    neu run
    ```

~ building
1. cd to main
2. build
    ```
    neu build --release
    ```

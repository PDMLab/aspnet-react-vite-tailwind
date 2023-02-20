# ASP.NET Core + React + vite + Tailwind CSS template

Template based on this [blog post](https://blog.codeinside.eu/2023/02/11/aspnet-core-react-with-vitejs/).

## Usage

### After first checkout

```bash
yarn
cd src/AspNetReactViteTailwind
dotnet restore
cd ui
yarn
```

### Starting dev environment

```bash
# from repository root folder
yarn start
```

This will bring up a `tmux` window with panes for the ASP.NET Server and the `vite` dev server.

![](assets/screenshot_tmux.png)

ASP.NET will open <https://localhost:5001/> in your default browser.

Then browse to <https://localhost:5001/app>:

![](assets/screenshot.png)
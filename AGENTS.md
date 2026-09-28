# Project information

- This is a Ukrainian-language educational ASP.NET Core MVC site targeting .NET 10.
- Build: `dotnet build --configuration Release` from the project directory.
- Run: `dotnet run --launch-profile http`. The local address is `http://localhost:5012`.
- The five page actions are `Index`, `About`, `Hobbies`, `Favorites`, and `Plans` in `Controllers/HomeController.cs`; each has its own Razor view in `Views/Home`.
- Shared navigation is in `Views/Shared/_Layout.cshtml`. Active links use `aria-current="page"`.
- Styling is in `wwwroot/css/site.css`; three local SVG illustrations are in `wwwroot/images`. No external assets or JavaScript are required for navigation.
- The user's name is Арсеній. Other personal details are sample content.
- The user prefers a simple design: standard fonts, modest headings, plain navigation, and minimal decoration.
- Verification: build, run, then verify HTTP 200 for `/`, `/Home/About`, `/Home/Hobbies`, `/Home/Favorites`, and `/Home/Plans`; check all five menu links on each page and ensure the stylesheet and all three images return HTTP 200.

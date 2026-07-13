# Asset Migration Report

## External image URLs replaced with local assets

| Original external image URL | New local filename | New relative path | Placeholder created |
| --- | --- | --- | --- |
| https://images.pexels.com/photos/6615086/pexels-photo-6615086.jpeg?auto=compress&cs=tinysrgb&w=1200 | hero-technical-work.svg | assets/images/backgrounds/hero-technical-work.svg | Yes |
| https://images.pexels.com/photos/3862373/pexels-photo-3862373.jpeg?auto=compress&cs=tinysrgb&w=900 | engineering-review.svg | assets/images/hero/engineering-review.svg | Yes |
| https://images.pexels.com/photos/19895882/pexels-photo-19895882.jpeg?auto=compress&cs=tinysrgb&w=800 | cad-workstation.svg | assets/images/about/cad-workstation.svg | Yes |
| https://images.pexels.com/photos/10497629/pexels-photo-10497629.jpeg?auto=compress&cs=tinysrgb&w=700 | workshop-tools.svg | assets/images/about/workshop-tools.svg | Yes |
| https://images.pexels.com/photos/5691622/pexels-photo-5691622.jpeg?auto=compress&cs=tinysrgb&w=900 | pda-test-fixture.svg | assets/images/portfolio/pda-test-fixture.svg | Yes |
| https://images.pexels.com/photos/669610/pexels-photo-669610.jpeg?auto=compress&cs=tinysrgb&w=900 | bom-preparation.svg | assets/images/portfolio/bom-preparation.svg | Yes |
| https://images.pexels.com/photos/7061662/pexels-photo-7061662.jpeg?auto=compress&cs=tinysrgb&w=900 | kitchen-rendering.svg | assets/images/portfolio/kitchen-rendering.svg | Yes |
| https://images.pexels.com/photos/2582937/pexels-photo-2582937.jpeg?auto=compress&cs=tinysrgb&w=900 | custom-pc-build.svg | assets/images/portfolio/custom-pc-build.svg | Yes |

## Notes
- The project now uses a local asset structure under assets/images for hero, about, portfolio, and backgrounds content.
- SVG placeholders were created so the site remains fully functional without broken image links.
- All image references in HTML and JavaScript now use relative paths.

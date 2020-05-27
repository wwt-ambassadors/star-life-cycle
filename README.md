![Build and Deploy](https://github.com/wwt-ambassadors/star-life-cycle/workflows/Build%20and%20Deploy/badge.svg?branch=master&event=push)

# Life Cycle of Stars Interactive

WWT-based interactive resource for exploring the life cycle of stars, created in collaboration with WGBH for NASA's Bringing the Universe to America's Classroom project.

http://projects.wwtambassadors.org/star-life-cycle/


## Building and Testing

In order to build and test the website, you need
[Node.js](https://nodejs.org/), specifically the `npm` command. If you need to
install Node.js, use your operating system’s package manager or visit
[nodejs.org](https://nodejs.org/) for installation instructions.

The first time you check out these files, run:

```
npm install
```

Once that has been done, you can build the website with:

```
npm run dist
```

To test the website locally, run the above and then:

```
npx http-server dist
```

You can then visit the URL printed out by the program to test out the web app
in your browser.


## Legalities

This code is licensed under the [MIT License]. The copyright to the original
WWT code is owned by the [.NET Foundation].

[MIT License]: https://opensource.org/licenses/MIT

## AAS WorldWide Telescope Acknowledgment

The AAS WorldWide Telescope system is a [.NET Foundation] project. Work on WWT
has been supported by the [American Astronomical Society] (AAS), the US
[National Science Foundation] (grants [1550701] and [1642446]), the
[Gordon and Betty Moore Foundation], and [Microsoft]. Established in 1899 and
based in Washington, DC, the AAS is the major organization of professional
astronomers in North America.

[American Astronomical Society]: https://aas.org/
[.NET Foundation]: https://dotnetfoundation.org/
[National Science Foundation]: https://www.nsf.gov/
[1550701]: https://www.nsf.gov/awardsearch/showAward?AWD_ID=1550701
[1642446]: https://www.nsf.gov/awardsearch/showAward?AWD_ID=1642446
[Gordon and Betty Moore Foundation]: https://www.moore.org/
[Microsoft]: https://www.microsoft.com/

## NASA Acknowledgment
The material contained in this product is based upon work supported by NASA under cooperative agreement award No. NNX16AD71A. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Aeronautics and Space Administration.


<p align="left"> 
  <img alt="Top Langs" height="150px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sashq-o&layout=compact&show_icons=true&theme=onedark" />
  <img alt="github stats" height="150px" src="https://github-readme-stats.vercel.app/api?username=Sashq-o&theme=onedark&show_icons=ture" />
  {
  user(login: "<YOUR USERNAME>") {
    repositories(ownerAffiliations: OWNER, isFork: false, first: 100) {
      nodes {
        name
        languages(first: 10, orderBy: {field: SIZE, direction: DESC}) {
          edges {
            size
            node {
              color
              name
            }
          }
        }
      }
    }
  }
}
</p>

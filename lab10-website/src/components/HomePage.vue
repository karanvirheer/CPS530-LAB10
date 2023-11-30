<template>
  <div>
    <h1>Vue Installation Process</h1>
    <ol>
      <li>Updated NVM</li>
      <li>
        Installed NPM here:
        <p>https://nodejs.org/en</p>
      </li>
      <li>
        Installed Vue using:
        <p>npm install -g @vue/cli</p>
      </li>
      <li>
        Created a Vue project using:
        <p>vue create lab10-website</p>
      </li>
      <li>
        Navigated into the Vue project directory using:
        <p>cd lab10-website</p>
      </li>
      <li>
        Ran the development server using:
        <p>npm run serve</p>
      </li>
      <li>
        Removed all boilerplate code and repurposed it with my own HTML and CSS
        <p>
          This step required me to learn about Vue and how its file structure
          works. More details about it are in the below section.
        </p>
      </li>
      <li>
        Host files on GitHub
        <p>This was done to host the website on GitHub Pages</p>
      </li>
    </ol>

    <h1>Difficulties and Solutions</h1>
    <ol>
      <li>
        Updating NPM
        <p>
          My initial installation of NPM was outdated and was throwing errors. I
          had to debug the issue and see why I was unable to update it. The
          issue was because my NVM version was outdated, so I simply updated it
          to the latest version. Then I re-ran the NPM update command (npm
          install -g npm@latest) and it worked from there.
        </p>
      </li>

      <li>
        Learning Vue Project Layout
        <p>
          The Vue project structure is complex compared to the simplistic file
          structures we've been working with so far. I had to watch some YouTube
          videos to become familiarized with the assets, components, router, and
          vues folders. After I was familiar, it was simple enough to add and
          remove the portions of the code that weren't necessary.
        </p>
      </li>
      <li>
        Webpage Hosting
        <p>
          Finding a free method of hosting my website required some research,
          but thankfully GitHub Pages was a quick solution. I hosted my Vue
          project on my GitHub repository, and from there I followed a tutorial
          to setup the GitHub pages portion. The only issue was finding a free
          website host, from there the actual hosting part was straight forward.
        </p>
      </li>
    </ol>
  </div>
</template>

<script>
export default {
  name: "HomePage",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  margin: 0;
}

ol {
  text-align: left;
}

p {
  font-weight: bold;
}
</style>

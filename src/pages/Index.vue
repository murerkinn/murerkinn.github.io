<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between items-center py-16 mb-10">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <h1 class="leading-tight">Hi, I'm</h1>
        <h2 class="text-indigo-600 leading-tight mb-3">Murat Erkin Cicek</h2>
        <h2 class="text-indigo-800 leading-tight">Full Stack Web Developer</h2>
      </div>

      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/web_developer.svg" alt="mobile" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner flex justify-between items-center mx-auto mb-10">
      <p class="text-lg sm:text-xl">
        I'm a hard-working web developer who loves creating elegant solutions in the least amount of time.
        I'm passionate about software architecture, web application security and cloud computing.
      </p>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="projects">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl space-y-6">
          <li class="flex">
            <span class="checkmark mr-3"></span>
            <div>
              <h3>Ecommerce Platform</h3>
              <p class="text-lg text-gray-600">
                An e-commerce application that I've made using React, Redux and Typescript in the frontend.
                In the backend I used Node.js, Express and MongoDB.
                Also I've used Docker to synchronize frontend and backend.
                You can view the Github repo of this project from <a href="https://github.com/murerkinn/react-commerce" target="_blank">here.</a>
              </p>
            </div>
          </li>
          <li class="flex">
            <span class="checkmark mr-3"></span>
            <div>
              <h3>Trello Clone</h3>
              <p class="text-lg text-gray-600">
                A trello clone which I've made to improve my Socket.io and MongoDB skills.
                In the frontend I used Vue and Ant-Design.
                In the backend I used Node.js, Express, MondoDB and Socket.io.
                You can view the Github repo for this project from <a href="https://github.com/murerkinn/trellone" target="_blank">here.</a>
              </p>
            </div>
          </li>
          <li class="flex">
            <span class="checkmark mr-3"></span>
            <div>
              <h3>Quo.vote</h3>
              <p class="text-lg text-gray-600">
                QuoVote is basically a Sli.do clone.
                But it prevents you to vote your own question or idea neither in a different browser nor in an incognito tab.
                QuoVote is not my own project, I'm one of the contributors of this project.
                You can view the Github repo of this project from <a href="https://github.com/nimbleturkiye/quovote" target="_blank">here.</a>
              </p>
            </div>
          </li>
          <li class="flex">
            <span class="checkmark mr-3"></span>
            <div>
              <h3>Frontend Mentor Challenges</h3>
              <p class="text-lg text-gray-600">
                I love taking designs and converting them to real websites.
                <a href="https://www.frontendmentor.io/profile/murerkinn" target="_blank">Here</a>, from my Frontend Mentor profile you can view the challenges I've completed so far.
              </p>
            </div>
          </li>
        </ul>
      </div>
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6" id="about">More about me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="https://avatars3.githubusercontent.com/u/57751146?s=460&u=01636b665628dea9b0eb61eac3d75b8bac8b0fe2&v=4" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">I'm a huge fan of Javascript. So my stacks are usually built on this. In frontend I'm comfortable with Vue, React and frameworks related to them like Nuxt.js, Next.js etc. Also in the backend I love using Node.js and Express.js. But I'm not limited with these. I also use PHP to create custom Wordpress themes and make apps with Laravel.</div>
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div class="contact-me bg-background-secondary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6" id="contact">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>

          <p class="mb-12">
            Please feel free to contact me. You can use the form below or send an email to <a href="mailto:murerkinn@gmail.com">me</a>.
          </p>

          <div class="text-lg sm:text-lg mb-16">
            <form action="#" class="mb-12">
              <div class="flex flex-wrap mb-6 -mx-4">
                  <div class="w-full md:w-1/2 mb-6 md:mb-0 px-4">
                      <label class="block mb-2 text-copy-primary" for="name">
                          Name
                      </label>

                      <input type="text" name="name" id="name" placeholder="Jon Snow" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-indigo-700 mb-2 p-4" required>
                  </div>

                  <div class="w-full px-4 md:w-1/2">
                      <label class="block text-copy-primary mb-2" for="email">
                          Email Address
                      </label>

                      <input type="email" name="email" id="email" placeholder="email@example.com"  class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none focus:border-indigo-700 mb-2 p-4" required>
                  </div>
              </div>

              <div class="w-full mb-12">
                  <label class="block text-copy-primary mb-2" for="message">
                      Message
                  </label>

                  <textarea id="message" rows="5" name="message" class="block w-full bg-background-form border border-border-color-primary shadow rounded outline-none appearance-none focus:border-indigo-700 mb-2 px-4 py-4" placeholder="Enter your message here." required></textarea>
              </div>

              <div class="flex justify-end w-full">
                  <input type="submit" value="Submit" class="block bg-indigo-700 hover:bg-indigo-800 text-white text-sm font-semibold tracking-wide uppercase shadow rounded cursor-pointer px-6 py-3">
              </div>
          </form>
          </div>
        </div>
      </div>
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>


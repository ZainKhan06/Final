<script setup>
import AboutItem from "./AboutItem.vue";
</script>

<template>
  <AboutItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Who Are We?</template>
    Programmatic is a nonprofit organization that provides free computer
    science education through classes hosted at schools and community spaces.
    We are committed to expanding access to high-quality STEM learning and
    helping students build strong academic and technical foundations.
    <a class="text-blue-500" href="#/team" type="link"><u>Meet our team</u>.</a>
  </AboutItem>

  <AboutItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Goals</template>

    Our mission is to cultivate student interest in computer science while
    building practical skills that support long-term success. We focus on
    structured instruction, project-based learning, and mentorship to prepare
    students for continued education and future careers.
  </AboutItem>
  <AboutItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Programs & Classes</template>

    Our programs are designed for students at different experience levels, from
    beginners to those ready for advanced topics. Course offerings include
    Python, Unity, Raspberry Pi, and related areas in software and hardware.
    Learn more
    <a class="text-blue-500" href="#/enroll" type="link"><u>here</u>.</a>
  </AboutItem>
  <AboutItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Future</template>

    As we grow, we plan to broaden our curriculum and serve additional
    communities. Our long-term objective is to provide equitable access to
    rigorous computer science education for as many students as possible.
  </AboutItem>
  <AboutItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Donations</template>

    Support our mission
    <a
      class="text-blue-500"
      href="https://hcb.hackclub.com/donations/start/programmatic"
      type="link"
      ><u>here</u></a
    >. Every contribution helps us keep classes free and accessible by funding
    curriculum resources, instructional materials, and student support.
  </AboutItem>
</template>

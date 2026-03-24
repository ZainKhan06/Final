<script setup>
import BioCard from "../components/BioCard.vue";
</script>

<template>
  <main class="flex OurTeam">
    <section class="fixed OurteamTxt">
      <h2 class="font-extrabold text-gray-200 text-6xl mt-32 ourTeamTitle">
        Meet the Team
      </h2>
      <h3
        class="text-lg font-bold py-10 ourTeam-desc text-gray-300 OurTeamDesc"
      >
        Programmatic is led by a team of founders, developers, and educators
        dedicated to delivering high-quality, student-centered computer science
        instruction. Together, we design curriculum, build learning tools, and
        continuously improve our programs to serve students effectively.
      </h3>
    </section>
    <section class="line"></section>
    <section class="flex flex-col gap-20 mt-36 mb-10 cards">
      <BioCard
        name="Ofir"
        pos="Founder, Front-End Developer, Teacher"
        desc="Ofir is a founder of Programmatic with more than five years of programming experience. He specializes in Python and is expanding his work in Unity and Dart to develop practical, student-focused projects."
        langs="Python, Dart, C#, JavaScript"
        discord="@.ofish"
        imgurl="discord.png"
      />
      <BioCard
        name="Zain"
        desc="Zain is a founder and instructor with three years of experience in Python and Raspberry Pi. He is committed to helping students build confidence through hands-on technology projects."
        langs="Python, Raspberry Pi, Circuits"
        discord="@zkzain06"
        pos="Founder, Front-End Developer, Teacher"
        imgurl="discord.png"
      />

      <BioCard
        name="Adam"
        desc="Adam is a founder and designer with approximately four years of Unity experience and a strong background in game development. He supports students in turning creative ideas into structured technical projects."
        langs="Python, C#"
        discord="@Adamimoka"
        pos="Founder, Graphic Designer, Front-End Developer"
        imgurl="discord.png"
      />

      <BioCard
        name="Ethan"
        desc="Ethan is a full-stack developer who maintains Programmatic's Discord bot and contributes to web application development that supports instruction and student engagement."
        langs="Python, C++, Java, JavaScript"
        discord="@ethqnol"
        pos="Full-Stack Developer, Dev of the Programmatic Discord Bot"
        imgurl="discord.png"
      />
    </section>
  </main>
</template>

<style scoped>
body {
  padding: 0;
  margin: 0;
}

.wrapper {
  display: flex;
}

nav {
  flex: 0 0 50vw;
  background: gray;
}

.nav-wrapper {
  position: fixed;
  top: 0;
  left: 0;
}

section {
  flex: 1 1;
}

/* media 1350 */

@media (max-width: 1350px) {
  .line {
    display: none;
  }

  .OurteamTxt {
    position: inherit;
  }

  .OurTeam {
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .cards {
    margin-top: 1rem;
  }

  .OurTeamDesc {
    width: 800px !important;
    max-width: 800px !important;
    text-align: center;
  }

  .ourTeamTitle {
    text-align: center;
  }

  /* media 1000px */
  @media (max-width: 1000px) {
    .OurTeamDesc {
      width: 600px !important;
      max-width: 600px !important;
    }
  }

  /* media 650px */
  @media (max-width: 650px) {
    .OurTeamDesc {
      width: 400px !important;
      max-width: 400px !important;
    }
  }

  /* media 450px */
  @media (max-width: 450px) {
    .OurTeamDesc {
      width: 370px !important;
      max-width: 370px !important;
    }
  }
}
</style>

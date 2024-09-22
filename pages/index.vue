<template>
  <div>
    <section
      class="grid px-12 py-12 text-yellow-100 md:px-16 lg:grid-cols-3 lg:px-48 xl:px-72"
    >
      <div class="col-span-2">
        <h2 class="text-4xl md:text-5xl">
          I'm G Krishna Adithya <br />
          — <br />
          Aspiring Software Engineer
        </h2>
        <h1 class="py-12 text-6xl md:text-[8rem] lg:text-[9rem]">
          Passionate
          <span
            class="bg-gradient-to-r from-yellow-100 to-blue-900 bg-clip-text font-extrabold tracking-wide text-transparent"
          >
            about
          </span>
          technology and
          <span
            class="bg-gradient-to-r from-blue-900 to-yellow-100 bg-clip-text font-extrabold tracking-wide text-transparent"
            >innovation.</span
          >
        </h1>
      </div>
    </section>

    <section
      class="bg-[#000000] bg-[radial-gradient(#ffffff33_1px,#00091d_1px)] bg-[size:20px_20px] py-12"
    >
      <h2
        class="pb-6 text-center text-4xl text-yellow-100 md:text-5xl lg:text-6xl"
      >
        Summary
      </h2>
      <p
        class="px-5 text-lg text-gray-300 md:px-24 md:text-xl lg:px-48 lg:text-2xl xl:px-96"
      >
        I'm a detail-oriented professional with a strong technical background, skilled in assessing processes, developing code logic, and improving
        product quality through automation. With excellent analytical and problem-solving abilities, I excel in meeting deadlines and delivering
        outstanding customer experiences. My passion for learning and adapting to new technologies makes me a valuable asset to any team.
      </p>
    </section>

    

    <section class="px-5 pb-12">
      <h2
        class="py-12 text-4xl text-yellow-100 md:text-5xl lg:px-24 lg:text-6xl xl:px-36"
      >
        Technical Experience
      </h2>
      <div class="grid grid-cols-1 gap-4 lg:grid-cols-2 xl:grid-cols-3">

        <!-- ProFinTech Technologies Experience -->
        <div class="flex items-center justify-center bg-black/30 p-3 duration-500 hover:bg-black/50">
          <div class="text-gray-500">
            <img src="public/images/profintech-logo.png" alt="ProFinTech Technologies Logo" class="h-16 mb-4" />
            <h3 class="text-xl font-bold">Software Developer Intern</h3>
            <p class="text-sm">ProFinTech Technologies · May 2024 - Aug 2024 · 4 months</p>
            <p>Hyderabad, Telangana, India · Remote</p>
            <p>
              As an SDE Intern, I worked with DBeaver for managing PostgreSQL databases, Postman API for testing, Apache Superset for data visualization, AWS EKS, Docker, and GitHub. I developed an API to read trade documents and process them using LLMs and Flask API, leading to a comprehensive understanding of the SDLC, including development, unit testing, and deployment.
            </p>
            <p>
              I created dashboards in Apache Superset for various organizational KPIs, enhancing my skills in data visualization and gaining experience in version control with GitHub.
            </p>
          </div>
        </div>

        <!-- Remotasks Experience -->
        <div class="flex items-center justify-center bg-black/30 p-3 duration-500 hover:bg-black/50">
          <div class="text-gray-500">
            <img src="public/images/remotasks-logo.png" alt="Remotasks Logo" class="h-16 mb-4" />
            <h3 class="text-xl font-bold">Reviewer</h3>
            <p class="text-sm">Remotasks · Nov 2023 - Apr 2024 · 6 months</p>
            <p>Remote</p>
            <p>
              As a Remotasks Reviewer, I worked on training LLMs by providing feedback and correcting labeled responses to improve accuracy. My primary focus was on code generation type labeling.
            </p>
          </div>
        </div>

        <!-- CyberGuard360 Experience -->
        <div class="flex items-center justify-center bg-black/30 p-3 duration-500 hover:bg-black/50">
          <div class="text-gray-500">
            <img src="/images/cg-logo.png" alt="CyberGuard360 Logo" class="h-16 mb-4" />
            <h3 class="text-xl font-bold">Student Researcher</h3>
            <p class="text-sm">CyberGuard360 · Feb 2023 - May 2023 · 4 months</p>
            <p>On-site</p>
            <p>
              As a Student Researcher, I contributed to data collection and analysis, focusing on cybersecurity topics, including the application of linear regression techniques.
            </p>
          </div>
        </div>

      </div>
    </section>

    <section class="pb-12">
  <h2
    class="px-5 py-12 text-center text-4xl text-yellow-100 md:text-5xl lg:px-24 lg:text-6xl xl:px-36"
  >
    Projects
  </h2>
  <div class="grid grid-cols-1 gap-4 lg:grid-cols-2 xl:grid-cols-3">
    
    <!-- Automated Interviewing Assessment System -->
    <div class="flex items-center justify-center bg-black/30 p-3 duration-500 hover:bg-black/50">
      <div class="text-gray-500">
        <strong>Automated Interviewing Assessment System:</strong>
        <p>
          Developed an innovative web application designed to help students prepare for interviews. The application leverages speech recognition technology to evaluate and provide feedback on interview responses, enhancing users' confidence and performance during real interviews.
        </p>
        <p>
          <strong>Technologies Used:</strong> Flask , JINJA , Web Speech API.
        </p>
        <p>
          <strong>Impact:</strong> Reduced the time and effort required for interview preparation, providing users with a simulated environment to practice and improve their skills.
        </p>
      </div>
    </div>

    <!-- Exam Answers Summarizer -->
    <div class="flex items-center justify-center bg-black/30 p-3 duration-500 hover:bg-black/50">
      <div class="text-gray-500">
        <strong>Exam Answers Summarizer:</strong>
        <p>
          Created a tool that summarizes lecture PDFs, significantly reducing the time students spend on note-taking. This application extracts key points and presents them in a concise format, making study sessions more efficient.
        </p>
        <p>
          <strong>Technologies Used:</strong> Python, Flask, OCR , PYPDF , HTML , CSS.
        </p>
        <p>
          <strong>Impact:</strong> Helped students focus on understanding core concepts rather than getting lost in excessive details, improving overall academic performance.
        </p>
        <p>
          <a href="https://examanswerssummarizer-2.onrender.com" class="text-blue-500 underline">View Project</a>
        </p>
      </div>
    </div>

    <!-- Recipe Maker -->
    <div class="flex items-center justify-center bg-black/30 p-3 duration-500 hover:bg-black/50">
      <div class="text-gray-500">
        <strong>Recipe Maker:</strong>
        <p>
          Developed a web application that generates creative recipes based on available ingredients. Users can input their ingredients, and the app suggests unique recipes, encouraging culinary creativity and reducing food waste.
        </p>
        <p>
          <strong>Technologies Used:</strong> StreamLit , Python , Gemini API
        </p>
        <p>
          <strong>Impact:</strong> Inspired users to cook more and waste less, fostering a greater appreciation for home cooking and creativity in the kitchen.
        </p>
        <p>
          <a href="https://iamhungry.streamlit.app/" class="text-blue-500 underline">View Project</a>
        </p>
      </div>
    </div>

    <!-- Visu Magic -->
    <div class="flex items-center justify-center bg-black/30 p-3 duration-500 hover:bg-black/50">
      <div class="text-gray-500">
        <strong>Visu Magic:</strong>
        <p>
          Created an application for text-to-image based search utilizing OpenAI’s CLIP architecture. Users can input text prompts, and the app generates relevant images, showcasing the potential of generative AI in creative fields.
        </p>
        <p>
          <strong>Technologies Used:</strong> Python, OpenAI's CLip , FAISS.
        </p>
        <p>
          <strong>Impact:</strong> Enabled users to visualize concepts and ideas more effectively, opening new avenues for creativity and artistic expression.
        </p>
      </div>
    </div>

  </div>
</section>
<section class="px-5">
      <h2
        class="px-5 py-12 text-4xl text-yellow-100 md:text-5xl lg:px-24 lg:text-6xl xl:px-36"
      >
        Technical Competency
      </h2>
      <div class="grid grid-cols-1 gap-4 lg:grid-cols-2 xl:grid-cols-3">
        <div
          class="flex items-center justify-center bg-black/30 p-3 duration-500 hover:bg-black/50"
        >
          <p class="text-gray-500">
            An intermediate in Java, Python, GitHub, Flask Framework, Apache Superset.<br />
            A beginner at JavaScript, HTML, CSS, React, Docker, AWS EC2.<br />
            Use of AI tools like ChatGPT, Gemini, Clip.<br />
            Software Development Fundamentals, Software Development Life Cycle, Unit Testing.<br />
            Understanding of Algorithms and Data Structures.<br />
            OS Knowledge – Working with Mac OS.
          </p>
        </div>
      </div>
    </section>
    <section class="pb-12">
      <h2
        class="px-5 py-12 text-center text-4xl text-yellow-100 md:text-5xl lg:px-24 lg:text-6xl xl:px-36"
      >
        Achievements
      </h2>
      <p class="text-gray-500 px-5 md:px-24 md:text-xl lg:px-48 lg:text-2xl xl:px-96">
        Received gold medals in competitive exams including Unified Council Olympiads, National Science Olympiads, and JEE-MAINS (top 5%). Achieved admission into NIT-W (but did not join due to COVID-19's impact).
      </p>
    </section>

    <section class="pb-12">
      <h2
        class="px-5 py-12 text-center text-4xl text-yellow-100 md:text-5xl lg:px-24 lg:text-6xl xl:px-36"
      >
        Contact Information
      </h2>
      <p class="text-gray-500 px-5 md:px-24 md:text-xl lg:px-48 lg:text-2xl xl:px-96">
        Phone: +91 9948348444<br />
        Location: Hyderabad, Telangana<br />
        Email: <a href="mailto:krishnaadithyag@gmail.com" class="text-blue-500 underline">krishnaadithyag@gmail.com</a><br />
        GitHub: <a href="https://github.com/G-KrishnaAdithya" class="text-blue-500 underline">G-KrishnaAdithya</a>
      </p>
    </section>
    <section class="pb-12">
  <h2
    class="px-5 py-12 text-center text-4xl text-yellow-100 md:text-5xl lg:px-24 lg:text-6xl xl:px-36"
  >
    Links
  </h2>
  <div
    class="mx-auto grid w-fit justify-center gap-x-24 gap-y-8 px-5 md:grid-cols-2 lg:grid-cols-3"
  >
    <a target="_blank" href="https://www.linkedin.com/in/krishna-adithya-gaddam-b5a9b7291/"
      ><img
        class="h-14 w-48"
        src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"
        alt="LinkedIn logo"
    /></a>
    <a target="_blank" href="https://github.com/G-KrishnaAdithya"
      ><img
        class="h-14 w-48"
        src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"
        alt="GitHub logo"
    /></a>
    <a
      target="_blank"
      class="flex h-14 w-48 flex-row items-center justify-center bg-gray-950 text-2xl font-bold uppercase tracking-widest"
      href="https://drive.google.com/file/d/1Dm_zSXWoqsh9xVhsVPkyyEw8diYznzpg/view?usp=drive_link"
      ><img
        class="mr-4 w-8"
        src="/images/pdf-file-svgrepo-com.svg"
        alt="PDF logo"
      />
      <span>Resume</span>
    </a>
    
  </div>
</section>


  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: "home",
});
</script>



<script setup>
import { MdSharpEmail } from '@kalimahapps/vue-icons';
import { BsPhoneFill } from '@kalimahapps/vue-icons';
import { CaLocationFilled } from '@kalimahapps/vue-icons';
import { AkLinkedInV1Fill } from '@kalimahapps/vue-icons';
import { AkGithubFill } from '@kalimahapps/vue-icons';
import { AiCvSquare } from '@kalimahapps/vue-icons';
import { FaComputerMouse } from '@kalimahapps/vue-icons';
import { JaFillComputerAlt } from '@kalimahapps/vue-icons';
import { LaMicrochipSolid } from '@kalimahapps/vue-icons';
import { BxSolidMicrochip } from '@kalimahapps/vue-icons';
import { BsClipboardCheckFill } from '@kalimahapps/vue-icons';
import { UnCalender } from '@kalimahapps/vue-icons';

</script>

<template>
  <div class="bg-gradient-to-r from-blue-100 via-white to-green-100 transition duration-50 ease-in-out p-10">
    <div class="grid grid-cols-8 gap-10">
      <div class="col-span-2">
        <img src="./assets/Fei.png" alt="self" class="rounded-full p-2 ml-8 mt-4" width="200px" height="200px">
      </div>
      <div class="col-span-6 ml-5">
        <div class="flex"> 
          <img src="./assets/software-dev.jpg" alt="self" class="rounded-full p-2" width="100px" height="100px">
          <p class="text-3xl ml-6">Wengang Fei</p>
        </div>
       
        <p class="text-sm mt-2">Software Developer</p>
        <p class="text-xs text-left">   
          I am a dedicated computer software developer with a strong command of JavaScript and proficiency in Vue/React.js,Visual Studio Code, and GitHub. Seeking a challenging role with a dynamic organization to leverage my skills and contribute to innovative projects. Passionate about problem-solving and eager to contribute to collaborative projects.
        </p>
      </div>
    </div>
    <hr class="my-2 border-blue-300 border-spacing-2 border-1">
    <div class="grid grid-cols-8">
      <div class="col-span-2 text-xs">
        <div class="flex">
          <img src="./assets/contact.webp" alt="contact" class="rounded-full" width="80px" height="50px"/>
          <p class="text-sm mt-4 ml-4">Contact</p>
        </div>
        <hr class="my-1 border-blue-300 border-spacing-2 border-1">
        <div class="flex mt-2"><MdSharpEmail class="mt-0.5"/>: wenfei@bu.edu</div>
        <div class="flex mt-2"><BsPhoneFill class="mt-0.5"/>: 617-369-2866</div>
        <div class="flex mt-2"><CaLocationFilled class="mt-0.5"/>: Boston MA</div>
        <div class="flex mt-2"><AkLinkedInV1Fill class="mt-0.5"/>:      
          <a href="https://www.linkedin.com/in/wengang-fei-9948701b4/" class="ml-0.5"> 
            <p class="text-blue-400">LinkedIn</p>
          </a>
        </div>
        <div class="flex mt-2"><AiCvSquare class="mt-0.5"/>:      
          <a href="https://wengangfei.github.io/CV/" class="ml-0.5"> 
            <p class="text-blue-400">CV Website</p>
          </a>
        </div>
        <div class="flex mt-2"><AkGithubFill class="mt-0.5"/>:      
          <a href="https://wengangfei.github.io/CV/" class="ml-0.5"> 
            <p class="text-blue-400">GitHub</p>
          </a>
        </div>
        <hr class="my-2 border-blue-300 border-spacing-2 border-1">
        <div class="mt">
          <div class="flex">
            <img src="./assets/education.jpg" alt="education" class="rounded-full" width="100px" height="55px">
            <p class="text-sm mt-4 ml-4">Education</p>
          </div>
          <hr class="my-1 border-blue-300 border-spacing-2 border-1">
          <p class="text-xs font-bold mt-2">Boston University</p>
          <p class="text-xs mt-1">BS in Computer Science</p>
          <p class="text-xs mt-1">09/2020 - 01/2024</p>
          <p class="text-xs mt-1">GPA: 3.6/4</p>
        </div>
        <hr class="my-2 border-blue-300 border-spacing-2 border-1">
        <div>
          <div class="flex">
            <img src="./assets/courses.webp" alt="skills" class="rounded-full p-2 mr-2" width="100px" height="100px">
            <p class="text-sm mt-4">Main Courses</p>
          </div>
          <hr class="my-1 border-blue-300 border-spacing-2 border-1">
          <div class="bg-blue-400 text-white px-2 text-xs mt-2 rounded-md">Software Dev.</div>
          <div class="bg-blue-400 text-white px-2 text-xs mt-2 rounded-md">Web App Dev.</div>
          <div class="bg-blue-400 text-white px-2 text-xs mt-2 rounded-md">Programming with C++</div>
          <div class="bg-blue-400 text-white px-2 text-xs mt-2 rounded-md">Computer networks</div>
          <div class="bg-blue-400 text-white px-2 text-xs mt-2 rounded-md">Data str with C++</div>
          <div class="bg-blue-400 text-white px-2 text-xs mt-2 rounded-md">Python str Information</div>
          <div class="bg-blue-400 text-white px-2 text-xs mt-2 rounded-md">JS and HTML with CSS</div>
          <div class="bg-blue-400 text-white px-2 text-xs mt-2 rounded-md">Computer Ope System</div>
          <div class="bg-blue-400 w-fit text-white px-2 text-xs mt-2 rounded-md">Etc......</div>
        </div>
        <hr class="my-2 border-blue-300 border-spacing-2 border-1">
        <div>
          <div class="flex">
            <img src="./assets/interests.png" alt="interests" class="rounded-full" width="100px" height="100px">
            <p class="text-sm mt-3 ml-4">Interests</p>
          </div>
          <hr class="my-1 border-blue-300 border-spacing-2 border-1">
          <div class="flex">
            <img src="./assets/ai.jpg" alt="ai" class="rounded-full p-2" width="65px" height="55px"> 
            <p class="text-xs mt-2">Communication</p>
          </div>
          <div class="flex">
            <img src="./assets/robotics.jpeg" alt="robot" class="rounded-full p-2" width="65px" height="55px"> 
            <p class="text-xs mt-2">Robotics</p>
          </div>
          <div class="flex">
            <img src="./assets/snowboarding.jpg" alt="ai" class="rounded-full p-2" width="65px" height="55px"> 
            <p class="text-xs mt-2">Snowboarding</p>
          </div>
          <div class="flex">
            <img src="./assets/games.jpeg" alt="ai" class="rounded-full p-2" width="65px" height="55px"> 
            <p class="text-xs mt-2">Video Games</p>
          </div>
        </div>
      </div>
      <div class="col-span-6 ml-8">
        <div>
          <p class="text-sm">My Strength and Weakness</p>
          <hr class="my-1 border-blue-300 border-spacing-2 border-1">
          <p class="text-xs mt-1">
          <span class="font-bold">Strength</span>:
          Proficiency in programming languages JavaScript, frameworks Vue.js, React.js, and Node.js, and database management skills like PGSQL,Knex.js.Demonstrated ability to debug complex code and optimize performance.Creative thinker in developing algorithms and scalable solutions. 
          <br />
          <span class="font-bold">Weakness</span>: I sometimes spend too much time perfecting details, which I’m addressing by prioritizing tasks based on impact.
          </p>
        </div>
        <div>
          <p class="text-sm mt-4">Work Experience</p>
          <hr class="my-1 border-blue-300 border-spacing-2 border-1">
          <div class="flex">
            <UnCalender />
            <p class="text-xs mt-1 ml-2">9/2022 - 11/2024</p>
          </div>
          <p class="text-xs mt-1"><span class="font-bold">Company</span>: 3D Fortify Printing</p>
          <p class="text-xs mt-1"><span class="font-bold">Position</span>: Software Developer</p>
          <p class="text-xs mt-1"><span class="font-bold">Location</span>: Charlestown, MA</p>
          <div class="text-xs mt-1">
            <span class="font-bold">Job Key Responsibilities:</span><br />
            <ul class="text-xs">
            <div class="flex mt-1">
              <FaComputerMouse class="mr-2 mt-0.5"/>
              <li>Develop front end Dashboard with Vue.js and tailwind CSS for 3D Fortify Printing clients.</li>
            </div>
            <div class="flex mt-1">
              <JaFillComputerAlt class="mr-2 mt-0.5"/>
              <li>Develop Back end with Node.js and Express.js.</li>
            </div>
            <div class="flex mt-1">
              <LaMicrochipSolid class="mr-2 mt-0.5"/>
              <li>Maintain the data base and sever on the Google Cloud Platform.</li>
            </div>
            <div class="flex mt-1">
              <BxSolidMicrochip class="mr-2 mt-0.5"/>
              <li>Database management with PGSQL and Knex.js.</li>
            </div>
            <div class="flex mt-1">
              <BsClipboardCheckFill class="mr-2 mt-0.5 ml-0.5"/>
              <li>Implement new features and bug fixes on client side and server side, maintain, improve existing features, and troubleshoot issues.
              </li>
            </div>
            </ul><br />
            <hr class="my-2 border-blue-300 border-spacing-2 border-1">
            <div>
              <ul class="text-sm mt-4 list-disc mb-2">Professional Skills</ul>
              <p class="font-bold">Programming Languages and App projects improvement:</p>
              <li>
              Proficient in HTML,CSS,JavaScript with experience in developing scalable and robust applications using object-oriented principles.
              </li>
              <li>
              Completes 95% of assigned tasks within agreed timelines, consistently meets deadlines and follows established processes and procedures.
              </li>
              <li>Receives positive feedback from team members for attention to detail nad ability to lean new tech-skills quickly.
              </li>
              <ul class="font-bold mt-2 list-disc">Web Development:</ul>
              <li>
              Skilled in front-end web development using HTML, CSS, JavaScript and Vue.js. Proficient in using Git and Github for version control.
              </li>
              <li>
              Assisted in the development and testing of software applications, ensuring adherence to coding standards and best practices.  
              </li>
              <p class="font-bold mt-2">Database Management:</p>
              <li>
              Experienced in designing and implementing database schemas, ensuring data integrity and security. Including PGSQL, Knex.js, and Node.js.
              </li>
              <li>
              Optimized database queries for efficient data retrieval and management.
              </li>
              <li>
              Collaborate with senior developer to implement new features and functionality in existing applications.
              </li>
            </div>
            <hr class="my-2 border-blue-300 border-spacing-2 border-1">
            <div class="flex">
              <hr class="my-2 border-blue-300 border-spacing-2 border-1">
              <div>
                <div class="flex">
                  <img src="./assets/tech-skills.png" alt="skills" class="rounded-full p-2 mr-2 mt-2" width="90px" height="100px">
                  <p class="text-sm mt-4">Technical Skills</p>
                  <p class="text-xs mt-4"></p>
                </div>
                <hr class="my-1 border-blue-300 border-spacing-2 border-1">
                <p class="text-xs mt-1">VS Code,Git,Github</p>
                <p class="text-xs mt-1">HTML,CSS,JavaScript</p>
                <p class="text-xs mt-1">Google Cloud Platform</p>
                <p class="text-xs mt-1">C++,Python,PHP</p>
              </div>
              <hr class="my-2 border-blue-300 border-spacing-2 border-1">
              <div class="ml-10">
                <div class="flex mt-1.5">
                  <img src="./assets/soft-skills.jpeg" alt="skills" class="rounded-full p-2 mr-2" width="90px" height="150px">
                  <p class="text-sm mt-3">Soft Skills</p>
                </div>
                <hr class="my-1 border-blue-300 border-spacing-2 border-1">
                <p class="text-xs mt-1">Communication</p>
                <p class="text-xs mt-1">Teamwork</p>
                <p class="text-xs mt-1">Confident</p>
                <p class="text-xs mt-1">Self-motivated</p>
                <p class="text-xs mt-1">Problem-solving</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  

</template>


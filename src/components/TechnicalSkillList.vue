<template>
    <TransitionGroup name="list" tag="ul"> 
        <div class="rounded-sm border-2 border-[#3BA576] bg-[#0d2118] px-4 py-2">
            <h2 class="text-2xl white font-bold py-2 px-4">
                <svg class="w-8 h-8 mr-1.5 flex-shrink-0 inline-block" aria-hidden="true" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path d="M17.982 18.725A7.488 7.488 0 0012 15.75a7.488 7.488 0 00-5.982 2.975m11.963 0a9 9 0 10-11.963 0m11.963 0A8.966 8.966 0 0112 21a8.966 8.966 0 01-5.982-2.275M15 9.75a3 3 0 11-6 0 3 3 0 016 0z" stroke-linecap="round" stroke-linejoin="round"></path>
                  </svg>
                Front-end 
            </h2>
            <ul class="max-w-md space-y-1 list-outside list-disc marker:text-white text-lg pl-4">
                <TechnicalSkillItem skill="HTML5">
                    <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/html-5.svg"/>
                </TechnicalSkillItem>  
                <TechnicalSkillItem skill="CSS">
                    <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/css-3.svg"/>
                </TechnicalSkillItem>
                <TechnicalSkillItem skill="TailwindCss">
                    <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/tailwindcss-icon.svg"/>
                </TechnicalSkillItem>
                <TechnicalSkillItem skill="Javascript">
                    <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/javascript.svg"/>
                </TechnicalSkillItem>      
                <TechnicalSkillItem skill="React.js">
                    <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/react.svg"/>
                </TechnicalSkillItem>  
                <TechnicalSkillItem skill="React-Spring">
                    <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/react-spring.svg"/>
                </TechnicalSkillItem>  
                <TechnicalSkillItem skill="Vue.js">
                    <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/vue.svg"/>
                </TechnicalSkillItem> 
                <TechnicalSkillItem skill="Swift">
                    <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/swift.svg"/>
                </TechnicalSkillItem>           
            </ul>
        </div>
      </TransitionGroup>
      <div class="rounded-sm border-2 border-[#3BA576] bg-[#0d2118] px-4 py-2">
        <h2 class="text-2xl white font-bold py-2 px-4">
              <svg class="w-8 h-8 mr-1.5 flex-shrink-0 inline-block" aria-hidden="true" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path d="M14.25 9.75L16.5 12l-2.25 2.25m-4.5 0L7.5 12l2.25-2.25M6 20.25h12A2.25 2.25 0 0020.25 18V6A2.25 2.25 0 0018 3.75H6A2.25 2.25 0 003.75 6v12A2.25 2.25 0 006 20.25z" stroke-linecap="round" stroke-linejoin="round"></path>
              </svg>
            Back-end 
        </h2>
        <ul class="max-w-md space-y-1 list-outside list-disc marker:text-white text-lg pl-4">
            <TechnicalSkillItem skill="Node.js">
                <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/nodejs-icon.svg"/>
            </TechnicalSkillItem>  
            <TechnicalSkillItem skill="Spring-Boot">
                <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/spring-icon.svg"/>
            </TechnicalSkillItem>
            <TechnicalSkillItem skill="Java">
                <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/java.svg"/>
            </TechnicalSkillItem>   
            <TechnicalSkillItem skill="Kotlin">
                <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/kotlin-icon.svg"/>
            </TechnicalSkillItem>        
        </ul>
    </div>
    <div class="rounded-sm border-2 border-[#3BA576] bg-[#0d2118] px-4 py-2">
        <h2 class="text-2xl white font-bold py-2 px-4">
              <svg class="w-8 h-8 mr-1.5 flex-shrink-0 inline-block" aria-hidden="true" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path d="M14.25 9.75L16.5 12l-2.25 2.25m-4.5 0L7.5 12l2.25-2.25M6 20.25h12A2.25 2.25 0 0020.25 18V6A2.25 2.25 0 0018 3.75H6A2.25 2.25 0 003.75 6v12A2.25 2.25 0 006 20.25z" stroke-linecap="round" stroke-linejoin="round"></path>
              </svg>
            Database
        </h2>
        <ul class="max-w-md space-y-1 list-outside list-disc marker:text-white text-lg pl-4">
            <TechnicalSkillItem skill="MySQL">
                <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/mysql.svg"/>
            </TechnicalSkillItem>
            <TechnicalSkillItem skill="MongoDB">
                <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/mongodb-icon.svg"/>
            </TechnicalSkillItem>    
            <TechnicalSkillItem skill="FireBase">
                <img class="w-4 h-4 mr-1.5 flex-shrink-0" src="../images/tech_icons/firebase.svg"/>
            </TechnicalSkillItem>            
        </ul>
    </div>
</template>

<script setup>
import TechnicalSkillItem from '../components/TechnicalSkillitem.vue'

</script>

<style scoped>
.list-enter-active,
.list-leave-active {
  transition: all 0.5s ease;
}
.list-enter-from,
.list-leave-to {
  opacity: 0;
  transform: translateX(30px);
}
</style>
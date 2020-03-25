<template>
    <div>
        <navbar/>
        <div class="bgColor">
            <!-- Shaw -->
            <div class="container-about">
                <div class="mt-16 md:flex">
                    <div class="md:flex-shrink-0">
                        <a href="https://www.behance.net/gallery/90457927/Do-Not-Disturb"><img class="rounded-lg md:w-64 w-full" src="../assets/prjImg/shawProj.png"></a>
                    </div>
                    <div class="mt-4 md:mt-0 md:ml-6">
                        <div class="uppercase tracking-wide text-sm font firstName font-bold">Shaw Industries</div>
                        <div class="block mt-1 text-lg leading-tight font-semibold text-gray-700">Do Not Disturb</div>
                        <p class="mt-2 text-gray-600">Do not disturb was a project done during my senior year of college in collaboration with Shaw Industries. The basis of the project was to create a system that integrated with Google Calendar to allow every room to have a notification on whether the room is being used or not.</p>
                    </div>
                </div>
            </div>

            <!-- MBI -->
            <div class="container-about">
                <div class="mt-16 md:flex">
                    <div class="md:flex-shrink-0">
                        <a href="http://mbiaccounting.000webhostapp.com/"><img class="rounded-lg md:w-64 w-full" src="../assets/prjImg/MBI.png"></a>
                    </div>
                    <div class="mt-4 md:mt-0 md:ml-6">
                        <div class="uppercase tracking-wide text-sm font firstName font-bold">MBI Accounting</div>
                        <div class="block mt-1 text-lg leading-tight font-semibold text-gray-700">Accounting Software</div>
                        <p class="mt-2 text-gray-600">MBI Accounting was a school project building a piece of accounting software. For this project the system was built using the CodeIgniter Framework for the backend as well as Bootstrap Framework for the front end. The site is live at <span class="text-blue-600"><a href="http://mbiaccounting.000webhostapp.com/">http://mbiaccounting.000webhostapp.com/</a></span>. To see an example, you can login with <br/>Username: Visitor <br /> Password: VisitorP@ss</p>
                    </div>
                </div>
            </div>

            <!-- Logo -->
            <div class="container-about">
                <div class="mt-16 md:flex">
                    <div class="md:flex-shrink-0">
                        <a href="https://linkedin.com/company/theragenics-costa-rica/"><img class="rounded-lg md:w-64 w-full" src="../assets/prjImg/TCLogo.png"></a>
                    </div>
                    <div class="mt-4 md:mt-0 md:ml-6">
                        <div class="uppercase tracking-wide text-sm font firstName font-bold">Theragenics Corporation Costa Rica</div>
                        <div class="block mt-1 text-lg leading-tight font-semibold text-gray-700">Logo Creation</div>
                        <p class="mt-2 text-gray-600">While in high school I got the opportunity to work with Theragenics Corporation to help create the company logo for their branch in Costa Rica.</p>
                    </div>
                </div>
            </div>

            <!-- Dad Jokes -->
            <div class="container-about">
                <div class="mt-16 md:flex">
                    <div class="md:flex-shrink-0">
                        <a href="https://admiring-hugle-9c7ef5.netlify.com/"><img class="rounded-lg md:w-64 w-full" src="../assets/prjImg/dadjokes.png"></a>
                    </div>
                    <div class="mt-4 md:mt-0 md:ml-6">
                        <div class="uppercase tracking-wide text-sm font firstName font-bold">Dad Jokes</div>
                        <div class="block mt-1 text-lg leading-tight font-semibold text-gray-700">Side Project</div>
                        <p class="mt-2 text-gray-600">Dad Jokes is a side project to help learn the different features of Vue, while also learning about pulling in data via Reddit API.</p>
                    </div>
                </div>
            </div>

            <!-- Daily Challenge -->
            <div class="container-about">
                <div class="mt-16 md:flex">
                    <div class="md:flex-shrink-0">
                        <a href="https://www.behance.net/CodyMullinProjects"><img class="rounded-lg md:w-64 w-full" src="../assets/prjImg/Day4.png"></a>
                    </div>
                    <div class="mt-4 md:mt-0 md:ml-6">
                        <div class="uppercase tracking-wide text-sm font firstName font-bold">Design Practice</div>
                        <div class="block mt-1 text-lg leading-tight font-semibold text-gray-700">Designing Practice</div>
                        <p class="mt-2 text-gray-600 pb-16">To make sure I am able to continuously practice my design skills, I enjoy doing mini design projects to make sure my skills always remain sharp and adjusting with the times. </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import navbar from '../components/navbar'
export default {
  components:{
    navbar
  }
}
</script>
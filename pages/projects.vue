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
                        <p class="mt-2 text-gray-600">MBI Accounting was a school project building a piece of accounting software. For this project the system was built using the CodeIgniter Framework for the backend as well as Bootstrap Framework for the front end. The site is live at <span class="text-blue-600"><a href="http://mbiaccounting.000webhostapp.com/">http://mbiaccounting.000webhostapp.com/</a></span>. To see an example, you can login with Username: Visitor <br /> Password: VisitorP@ss</p>
                    </div>
                </div>
            </div>

            <!-- Logo -->
            <div class="container-about">
                <div class="mt-16 md:flex">
                    <div class="md:flex-shrink-0">
                        <img class="rounded-lg md:w-64 w-full" src="../assets/prjImg/TCLogo.png">
                    </div>
                    <div class="mt-4 md:mt-0 md:ml-6">
                        <div class="uppercase tracking-wide text-sm font firstName font-bold">Theragenics Corporation Costa Rica</div>
                        <div class="block mt-1 text-lg leading-tight font-semibold text-gray-700">Logo Creation</div>
                        <p class="mt-2 text-gray-600"></p>
                    </div>
                </div>
            </div>

            <!-- Theragenics -->
            <div class="container-about">
                <div class="mt-16 md:flex">
                    <div class="md:flex-shrink-0">
                        <img class="rounded-lg md:w-64 w-full" src="../assets/prjImg/Day4.png">
                    </div>
                    <div class="mt-4 md:mt-0 md:ml-6">
                        <div class="uppercase tracking-wide text-sm font firstName font-bold">Design Practice</div>
                        <div class="block mt-1 text-lg leading-tight font-semibold text-gray-700">Designing Practice</div>
                        <p class="mt-2 text-gray-600">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsa voluptas quaerat natus itaque dicta eligendi? Temporibus, libero. Necessitatibus, cupiditate voluptates.</p>
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
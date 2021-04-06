<template>

    <header>
        <nav-bar/>
    </header>

    <main>
        <!-- Left-Content Starts Here -->
        <div class="left-content">
            <user-box/>
            <user-folders/>
         </div>
        <!-- Center-Content Starts Here -->
        <div class="center-content">
            <post-text-box/>
            <posts/>
        </div>
        <!-- Right-Content Starts Here -->
         <div class="right-content">
             <events-warn/>
        </div>
    </main>
   
</template>
<script>

import NavBar      from '@/Components/NavBar'
import UserBox     from '@/Components/UserBox'
import UserFolders from '@/Components/UserFolders'
import PostTextBox from '@/Components/PostTextBox'
import Posts       from '@/Components/Posts'
import EventsWarn  from '@/Components/EventsWarn'

export default ({
    components:{
        NavBar,
        UserBox,
        UserFolders,
        PostTextBox,
        Posts,
        EventsWarn,
    }
})
</script>

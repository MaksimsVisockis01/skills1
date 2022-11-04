<template>
<body>
    
    <h1 class="Roadmap">Roadmap</h1>
    <a href="https://www.isaacnc.com/" target="_blank" class="isaac">By Isaac N.C. Visit website</a>

    <!-- Backlog -->
    <div class="Backlog Boxes">
        <a class="TitleBacklog Titles">Backlog</a>
            <div class="ticket1 card">
                <p class="Boxheader1 Headers">Twilio integration</p>
                    <p class="BoxText1 Text">Create new note via SMS. Support text, audio, links, and media.</p>
            </div>
                <div class="ticket2 card">
                    <p class="Boxheader2 Headers">Markdown support</p>
                        <p class="BoxText2 Text">Markdown shorthand converts to formatting</p>
                            <button class="BoxButton1 Buttons">Formatting</button>
                </div>
    </div>

    <!-- To do -->
    <div class="ToDo Boxes">
        <a class="TitleToDo Titles">To do</a> 
            <div class="ticket3 card">
                <p class="Boxheader3 Headers">Tablet view</p>
            </div>

            <div class="ticket4 card">
                <p class="Boxheader4 Headers">Audio recording in note</p>
                    <p class="BoxText3 Text">Show audio in a note and playback UI</p>
                        <button class="BoxButton2 Buttons">Note interface</button>
            </div>

            <div class="ticket5 card">
                <p class="Boxheader5 Headers">Bookmark in note</p>
                    <p class="BoxText4 Text">Show rich link UI in a note, and feature to render website screenshot.</p>
                        <button class="BoxButton3 Buttons">Note interface</button>
            </div>

            <div class="ticket6 card">
                <p class="Boxheader6 Headers">Image viewer</p>
                    <p class="BoxText5 Text">Opens when clicking on the thumbnail in the list or on the image in the note</p>
            </div>
    </div>

    <!-- In progress -->
    <div class="InProgress Boxes">
        <a class="TitleInProgress Titles">In progress</a>
            <div class="ticket7 card">
                <p class="Boxheader7 Headers">Mobile view</p>
                    <p class="BoxText6 Text">Functions for both web responsive and native apps. Note: Android and iOS will need unique share icons.</p>
            </div>
            <div class="ticket8 card">
                <p class="Boxheader8 Headers">Desktop view</p>
                    <p class="BoxText7 Text">PWA for website and native apps. Note: Windows and Mac will need unique share icons.</p>
            </div>
            <div class="ticket9 card">
                <p class="Boxheader9 Headers">Formatting options</p>
                    <p class="BoxText8 Text">Mobile formatting bar expands and collapses when tapping the format icon.</p>
            </div>
            <div class="ticket10 card">
                <p class="Boxheader10 Headers">Media in note</p>
                    <p class="BoxText9 Text">Image & video with player UI</p>
                        <button class="BoxButton4 Buttons">Note interface</button>
            </div>
    </div>

    <!-- Designed -->
    <div class="Designed Boxes">
        <a class="TitleDesigned Titles">Designed</a>
            <div class="ticket11 card">
                <p class="Boxheader11 Headers">Audio recording</p>
                    <p class="BoxText10 Text">Interface for when recording a new audio note</p>
                        <button class="BoxButton5 Buttons">New note</button>
            </div>
            <div class="ticket12 card">
                <p class="Boxheader12 Headers">Bookmarking</p>
                    <p class="BoxText11 Text">Interface for when creating a new link note.</p>
                        <button class="BoxButton6 Buttons">New note</button>
            </div>
            <div class="ticket13 card">
                <p class="Boxheader13 Headers">Mobile home screen</p>
                    <p class="BoxText12 Text">Folders, tags, and notes lists are sorted by recent.</p>
            </div>
    </div>
</body>

</template>

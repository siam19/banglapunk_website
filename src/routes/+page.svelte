<h2>BanglaPunk</h2>
<div class="logo">
    
    <!-- Generator: Adobe Illustrator 28.1.0, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
    <svg version="1.1" id="Layer_2"    xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
     viewBox="0 0 3000 3000" style="enable-background:new 0 0 3000 3000;" xml:space="preserve">
    <defs>
        <filter id="red-glow" filterUnits="userSpaceOnUse"
                x="-50%" y="-50%" width="200%" height="200%">
            <!-- blur the text at different levels-->
            <feGaussianBlur in="SourceGraphic" stdDeviation="5" result="blur5"/>
            <feGaussianBlur in="SourceGraphic" stdDeviation="10" result="blur10"/>
            <feGaussianBlur in="SourceGraphic" stdDeviation="20" result="blur20"/>
            <feGaussianBlur in="SourceGraphic" stdDeviation="30" result="blur30"/>
            <feGaussianBlur in="SourceGraphic" stdDeviation="50" result="blur50"/>
            <!-- merge all the blurs except for the first one -->
            <feMerge result="blur-merged">
                <feMergeNode in="blur10"/>
                <feMergeNode in="blur20"/>
                <feMergeNode in="blur30"/>
                <feMergeNode in="blur50"/>
            </feMerge>
            <!-- recolour the merged blurs red-->
            <feColorMatrix result="red-blur" in="blur-merged" type="matrix"
                           values="1 0 0 0 0
                                   0 0.4 0 0 0
                                   0 0 0.44 0 0
                                   0 0 0 1 0" />
            <feMerge>
                <feMergeNode in="red-blur"/>       <!-- largest blurs coloured red -->
                <feMergeNode in="blur5"/>          <!-- smallest blur left white -->
                <feMergeNode in="SourceGraphic"/>  <!-- original white text -->
            </feMerge>
        </filter>
    </defs>
    <style type="text/css">
        
        
    
    </style>
    <path class="st0" d="M2851.17,1780.08c147.43-695.99-757.3-1429.94-1323.44-1733.03C992.37,453.57,142.64,945.22,235.35,1720.2
        c20.61,269.97,377.74,593.4,574.45,735.43c-28.76,72.87-682.52,654.49-265.52,456.39c611.78-187.83,1329.62,10.72,1972.5-6.79
        c143.8-51.99-217.96-360.87-263.14-447.02C2482.64,2329.39,2811.64,2051.09,2851.17,1780.08z M2130.27,2423.2
        c945.46,713.52-1018.3,221.84-1507.14,415.38c109.27-138.95,213.91-272.01,315.83-401.63c-73.63-38.73-148.86-72.87-218.26-116.33
        C1.58,1791.87,382.48,1076.82,920.47,605.98c188.54-165.01,370.49-384.3,599.63-458.26
        C2384.92,612.84,3433.64,1851.9,2130.27,2423.2z"/>
</svg>

    

</div>
<div class="text centered"><a href="https://www.instagram.com/banglapunk">Visit Store</a></div>


<style>
    h2 {
        text-align: center;
        font-size: 28pt; 
        color: white;
        display: block;
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translate(-50%, 0%);
    }
    .st0{fill:#FFFFFF;}
    #Layer_2:hover{
        filter: url(#red-glow);
        transition: all 0.8s ease;;}
        
    .logo {
        scale: 0.4;
        margin-top: -52vh;
    }


    .text {
        font-size: 48pt;
        text-align: center;

    }
    @media (max-width: 960px) {
        .logo {
        scale: 1;
        margin-top: 27vh;

        }
        .text {
        font-size: 34pt;
        text-align: center;

    }
    .centered {
        position: fixed; /* or absolute */
        top: 50%;
        left: 50%;
        /* bring your own prefixes */
        transform: translate(-50%, -50%);
        }
    }
    


    a {
        color: white;
        text-decoration: none;
    }
    a:hover {
        background-color: blue;
        transition: all 0.3s ease;
        border-radius: 10px;
        padding: 5px;
    }
 
    

</style>



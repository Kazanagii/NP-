# NP
/* Remove the (useless) level indicator */
span.userlevel {display:none;}

/* Remove avatars, but make backgrounds more opaque, basically replacing them */
.postblock-read .postrender .postinner>.postuser .background-image:before,
.postrender .postinner>.postuser .background-image:before,
.postrender .postinner>.postuser .postavatar{opacity: 0;}

/* Improve username legibility on backgrounds, by selectively applying textshadowing
aswell as using brighter colours and making everything a note bigger */
.postrender .postinner > .postuser .username{font-weight:normal;font-size:1.23rem;}
.username.user-gold a{color:#eb2;}
.username.user-moderator a, .username.user-admin a{color:#0a0;}
.username a{color:#39e;}
.has-background-image .username {text-shadow: 002px black;}

/* fixes the shit cropping */
.postrender .postinner > .postuser .background-image{background-size:100%; background-repeat:no-repeat;}
.postblock-read .postrender .postinner>.postuser .background-image:after{background:linear-gradient(to bottom, rgba(230,230,230,0), #e6e6e6390px)}
.postrender .postinner > .postuser .background-image:after{background:linear-gradient(to bottom, rgba(230,230,230,0), #e6e6e6390px)}

/* minimalistic profile cards */
.postuser .user-card .user-card-header{padding-left:0!important; padding-right:0!important;margin-top:0; background-color: #0000}
.postuser .user-card .user-card-toolbar{background-color: #0000}
.postuser .user-card {background:none !important; box-shadow:unset; width:200px; left:0; top:0; height:110px; background-color: rgba(34,34,34,0.3) !important}

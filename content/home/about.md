+++
# About/Biography widget.

date = "2016-04-20T00:00:00"
draft = false

widget = "about"

# Order that this section will appear in.
weight = 1


# List your qualifications (such as academic degrees).
[[education.courses]]
  course = "B.Sc. in Computer Engineering"
  institution = "Iowa State University"
  year = 2017

# List your academic interests.
[interests]
  interests = [
  "Big Data",
  "Cloud Computing",
  "Mobile and IoT Applications",
  ]
 
+++

<div id="biography">
    <h1>Biography</h1>
    <p>
        I am a Software Developer with a demonstrated history of working in the higher education industry. Skilled in web technologies (LAMP Stack, Java, and Python), Big data processing (Hadoop Eco System) and exposed to embedded programming. Strong engineering professional with a Bachelor’s Degree focused in Computer Engineering from Iowa State University.
    </p>
</div>

<script>
$(document).ready(function(){
    if($( "#biography" ).isInViewport().length > 0){
        $( "#biography" ).addClass( "animated fadeInUp" );
    }
    if($( "#interests" ).isInViewport().length > 0){
        $( "#interests" ).addClass( "animated fadeInUp" );
    }
    if($( "#grad" ).isInViewport().length > 0){
        $( "#grad" ).addClass( "animated fadeInUp" );
    }
});
</script>

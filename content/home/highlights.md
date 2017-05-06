+++
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.

date = "2016-04-20T00:00:00"
draft = false

title = "Highlights"
subtitle = ""
widget = "custom"

# Order that this section will appear in.
weight = 2

+++
<style>
.text-muted{
    color: white;
}
</style>
<ul class="timeline ">
    <li id="web_dev">
      <div class="timeline-badge" style="background-color: #F29F05"><i class="fa fa-server" aria-hidden="true"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading" style="background-color: #F29F05">
          <h4 class="timeline-title">Backend Developer
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Spring '16 - Present</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Develop web software at Iowa State University</p>
        </div>
      </div>
    </li>
    <li class="timeline-inverted" id="college">
    <div class="timeline-badge" style="background-color:#E82935;"><i class="fa fa-graduation-cap" aria-hidden="true"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading" style="background-color: #E82935">
          <h4 class="timeline-title">Computer Engineering
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Fall '13 - Spring '17</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Bachelor of Science from Iowa State University</p>
        </div>
      </div>
    </li>
    <li id="leader">
      <div class="timeline-badge" style="background-color:#F25C05;"><i class="fa fa-group" aria-hidden="true"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading" style="background-color:#F25C05">
          <h4 class="timeline-title">Project Leader
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Fall '16 - Spring '17</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Lead team through software design and implementation</p>
        </div>
      </div>
    </li>
    <li class="timeline-inverted" id="honor">
      <div class="timeline-badge" style="background-color:#9E1B1B"><i class="fa fa-trophy" aria-hidden="true"></i></div>
      <div class="timeline-panel">
        <div class="timeline-heading" style="background-color: #9E1B1B">
          <h4 class="timeline-title">Deans List Honor
            <p><small class="text-muted"><i class="glyphicon glyphicon-time"></i>&nbsp;Fall '16</small></p>
          </h4>
        </div>
        <div class="timeline-body">
          <p>Deans List Honor Recipient</p>
        </div>
      </div>
    </li>
</ul>

<script>
$(document).ready(function(){
    $(window).scroll(function() {
        if($( "#web_dev" ).isInViewport().length > 0){
            $( "#web_dev" ).addClass( "animated flipInX" );
        }
        if($( "#honor" ).isInViewport().length > 0){
            $( "#honor" ).addClass( "animated flipInX" );
        }
        if($( "#leader" ).isInViewport().length > 0){
            $( "#leader" ).addClass( "animated flipInX" );
        }
        if($( "#college" ).isInViewport().length > 0){
            $( "#college" ).addClass( "animated flipInX" );
        }
    });
});
</script>
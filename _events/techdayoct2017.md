---
layout: events
title: K-MUG TechDay - Saturday 21 October 2017
eventDate : 21st October 2017
date : 2017-10-21
eventOrder: 11
image: '../events/techday-oct-2017/banner.jpg'
---

<div class="col-lg-10 col-lg-offset-1 text-center">
  <table class="table"> 
  <tr>
      <td colspan="2"><h5>Agenda</h5></td>
  </tr>
  <tr>
      <td class="col-md-6">9:30 AM - 9:45 AM</td>
      <td class="col-md-6">Registration & Networking</td>
  </tr>
  <tr>
    <td class="col-md-6">9:45 AM - 11:00 AM</td>
    <td class="col-md-6">Umbraco CMS - Abhilash Ashok</td>
  </tr>
  <tr>
    <td class="col-md-6">11:00 AM - 11:15 AM</td>
    <td class="col-md-6">Coffee & Networking Break</td>
  </tr>
  <tr>
    <td class="col-md-6">11:15 AM - 12:15 PM</td>
    <td class="col-md-6">Machine Learning: Pros & Cons - Praseed Pai</td>
  </tr>
  <tr>
    <td class="col-md-6">12:15 PM - 01:30 PM</td>
    <td class="col-md-6">Angular Programming - Shalvin P D</td>
  </tr>
  <tr>
    <td class="col-md-6">01:30 PM - 02:00 PM</td>
    <td class="col-md-6">Ask the experts - Team</td>
  </tr>
</table>
    <table class="table">
        <tr><td colspan="2"><h5>Register @ <a href="http://k-mug.net/register">http://k-mug.net/register</a></h5></td></tr>
    </table>
        <table class="table">
        <tr><td colspan="2"><h5>Venue</h5></td></tr>
        <tr><td colspan="2">
        <h3>Orion India Systems Pvt. Ltd</h3>
        2nd Floor, LuLu Cyber Tower
        Infopark, Kakkanad, Kochi
        India, 682042
        </td></tr>
    </table>
<table class="table">
        <tr>
            <td colspan="2"><h5>Speakers</h5></td></tr>
        <tr><td class="col-md-3">
            <img src="../../img/people/abhilash.jpg" alt="Abhilash" style="width:140px; height:140px" class="img-thumbnail" />
        </td><td class="col-md-9 text-justify">Abhilash Ashok is a passionate Microsoft Technology Enthusiast working as User Experience Lead at Identitymine, Kochi. He has 8 years of rich experience in Microsoft Technologies. His area of expertise includes Windows Phone, Windows Store, Kinect for Windows, Xamarin, WPF, ASP.NET and legacy technologies like Windows Forms. He blogs at <a href="http://cametoofar.com/" target="_blank">cametoofar.com</a>.
        <br>His presentation document is available @ <a href="https://www.slideshare.net/secret/zMHe2MuEnfi3DA" target="_blank">Umbraco CMS</a></td></tr>
          <tr><td class="col-md-3">
            <img src="../../img/people/praseed.jpg" alt="Praseed" style="width:140px; height:140px" class="img-thumbnail" />
        </td><td class="col-md-9 text-justify">Praseed Pai, a Software Product Engineering/Re-engineering professional with good Business accumen, Technical competancy and Software Engineering Skills with exposure to shrink wrapped product development, IT services, Application Service Providers, Captives and Staff augmentation. <a href="http://slangfordotnet.codeplex.com/" target="_blank">SLANGFORDOTNET</a>.
        <br>His presentation document is available @ <a href="https://www.slideshare.net/secret/IE0ThTUJYZkkau" target="_blank">Machine Learning: Pros & Cons</a></td></tr> 
         <tr><td class="col-md-3">
            <img src="../../img/people/shalvin.jpg" alt="Shalvin" style="width:140px; height:140px" class="img-thumbnail" />
        </td><td class="col-md-9 text-justify">Shalvin PD is working as Independent .NET Corporate Trainer and Consultant with more than 15 years of experience is Microsoft Technolgies. Specializing in ASP .NET, WPF, Silverlight, Sharepoint, Entity Framework, etc. Actively associates with Microsoft User Group movement in Kerala from its very inception. He is a frequent speaker, blogger and a .Net enthusiast.  He blogs at <a href="http://shalvinpd.blogspot.in/" target="_blank">shalvinpd.blogspot.in</a>.
        <br>His presentation document is available @ <a href="https://docs.google.com/presentation/d/e/2PACX-1vR2kzSZ3it9ekE_95-U_iJ-mAkAaO4T2FhOWyQwhQrI2El9MmXpb70cDE4Do7i_3JN88dvcKHw-ZfuG/pub?start=false&loop=false&delayms=3000&slide=id.p" target="_blank">Angular 4</a></td></tr>       
    </table>
    <table class="table">
        <tr><td colspan="2"><h5>Photos</h5></td></tr>
        <tr><td colspan="2">
        {% assign photos = (site.data.photos | where: "name" , "Techday October 2017") %}
        {% for photo in photos %}
            <div id="{{ photo.name | replace:' ','-' }}"></div><br/><br/>
            <div class="col-lg-10 col-lg-offset-1">
            <h4>{{ photo.name }}</h4>
            </div>

            <div class="row">
            {% for img in photo.photos %}
                <div class="col-xs-6 col-md-3">
                    <img class="img-thumbnail" style="cursor:pointer" 
                        src="{{ img.url }}" alt="{{ img.title }}" />
                </div>
            {% endfor %}
            </div>
        {% endfor %}
        </td></tr>
    </table>
</div>

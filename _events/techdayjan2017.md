---
layout: events
title: K-MUG TechDay January 2017
eventDate : 21st January 2017
date : 2017-01-21
eventOrder: 1
image: '../events/techday-jan-2017/6.jpg'
---
<div class="col-lg-10 col-lg-offset-1 text-center">
    <table class="table">
        <tr><td colspan="2"><h5>Agenda</h5></td></tr>
        <tr><td class="col-md-6">9:30 AM - 9:45 AM</td><td class="col-md-6">Networking and Community Updates</td></tr>
        <tr><td class="col-md-6">9:45 AM - 10:30 AM</td><td class="col-md-6">Block Chain and Eethereum - Praseed Pai</td></tr>
        <tr><td class="col-md-6">10:30 AM - 11:15 AM</td><td class="col-md-6">ASP.NET Core and Angular - Shalvin</td></tr>
        <tr><td class="col-md-6">11:15 AM - 11:25 AM</td><td class="col-md-6">Tea Break and Networking</td></tr>
        <tr><td class="col-md-6">11:25 AM - 12:00 PM</td><td class="col-md-6">JVM Internals - Sarath</td></tr>
        <tr><td class="col-md-6">12:00 PM - 12:40 PM</td><td class="col-md-6">Office 365 Development - Abhilash Ashok</td></tr>
        <tr><td class="col-md-6">12:40 PM - 1 PM</td><td class="col-md-6">Ask Experts - Q&amp;A Session</td></tr>
    </table>
    <table class="table">
        <tr><td colspan="2"><h5>Speakers</h5></td></tr>
        <tr><td class="col-md-3">
            <img src="../../img/people/abhilash.jpg" alt="Abhilash" style="width:140px; height:140px" class="img-thumbnail" />
        </td><td class="col-md-9 text-justify">Abhilash Ashok is a passionate Microsoft Technology Enthusiast working as User Experience Lead at Identitymine, Kochi. He has 8 years of rich experience in Microsoft Technologies. His area of expertise includes Windows Phone, Windows Store, Kinect for Windows, Xamarin, WPF, ASP.NET and legacy technologies like Windows Forms. He blogs at http://cametoofar.com/.</td></tr>
         <tr><td class="col-md-3">
            <img src="../../img/people/shalvin.jpg" alt="Shalvin" style="width:140px; height:140px" class="img-thumbnail" />
        </td><td class="col-md-9 text-justify">Shalvin PD is working as Independent .NET Corporate Trainer and Consultant with more than 15 years of experience is Microsoft Technolgies. Specializing in ASP .NET, WPF, Silverlight, Sharepoint, Entity Framework, etc. Actively associates with Microsoft User Group movement in Kerala from its very inception. He is a frequent speaker, blogger and a .Net enthusiast.  He blogs at http://shalvinpd.blogspot.in/.</td></tr>
    </table>
    <table class="table">
        <tr><td colspan="2"><h5>Venue</h5></td></tr>
        <tr><td colspan="2">
        Orion India Systems Pvt. Ltd
        2nd Floor, LuLu Cyber Tower
        Infopark, Kakkanad, Kochi
        India, 682042
        </td></tr>
    </table>
    <table class="table">
        <tr><td colspan="2"><h5><a href="https://kumgtechdayjan2017.eventbrite.com">Register</a></h5></td></tr>
    </table>
<table class="table">
        <tr><td colspan="2"><h5>Photos</h5></td></tr>
        <tr><td colspan="2">
        {% assign photos = (site.data.photos | where: "name" , "Techday January 2016") %}
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

### SOFTWARE REQUIREMENTS SPECIFICATION

# Washita

### *Project Functional Requirement Specification , Version 1*
 
##### Prepared by: O.Semenova

 
 

 
Contents
1. [Purpose of the document](#Purpose-of-the-document)
2. [Project Overview](#Project-Overview)  
2.1 [Audience](#Audience)  
2.2 [Hardware and Hosting](#Hardware-and-Hosting)
3. [Information Architecture](#InformationArchitecture)
3.1 [Washita site](#Washita-site)
3.1.1 [Washita](#Washita)
3.1.2 Photograph
3.1.3 Contact Details
3.1.4 Emergency Contact
3.1.5 Dependents
3.1.6 Immigration
3.1.7 Job
3.1.8 Salary
3.1.9 Report To
3.1.10 Qualifications
3.1.11 Membership 19
4. Site Design 20
4.1 Aesthetic/HTML Requirements and Guidelines 20

 

# 1. <a name="Purpose-of-the-document"></a> Purpose of the document:

This is not a project plan. It is a guide for system architecture and development, not for phasing, timelines or deliverables.
 
This document is divided into three sections:
+ Project Overview
+ Information Architecture
+ Site Design









# 2. <a name="Project-Overview"></a> Project Overview:

### 2.1 <a name="Audience"></a> Audience:
This document is intended as a complete guide for customers using Washita.cl 1.0. By reading this guide, you will learn how to use Washita.cl through the elements of the graphical user interface and what's behind some of the advanced features that are not always obvious at first sight. It will hopefully guide you around some common problems that frequently appear for users of Washita.cl.

### 2.2 <a name="Hardware-and-Hosting"></a> Hardware and Hosting:
 
Washita’s servers will be hosted at **X** company’s site.  
**Washita will be hosted on two servers: One to host the actual website and (language)code, and the other to host the (database name)database.**


# 3. <a name="InformationArchitecture"></a> Information Architecture

Visit http://washita.cl site

### 3.1 <a name="Washita-site"></a> Washita site

Washita is a powerful tool providing its customers with the ability to have their clothes, linen and home items to be washed, ironed, well folded and specially cleaned. The service offers **free** collection and delivery. Customers’ household laundry is picked up at their premises and delivered back minimum in two days.
Those who wish to use the service do not need register in. Therefore, this makes the application simplier to use. However, personal accounts are available on the site, where customers can find the history of their orders.

##### 3.1.1 <a name="Washita"></a> Washita

When a Washita-User visits  the site for the first time, the first thing they will see is the main page  as shown in Figure 1. They are able to scroll down the page for more information or click tabs.  In addition, a user can register in.
 
 
 
 
![Figure 1](images/Figure1.png)
   
 
3.1.2 ”Fácil y rápido” / “Easy and fast”
The Washita-user can scroll down to this section or click tab “Cómo Funciona” or click button “Cómo funciona”
Figure 2:
 
The Washita-user will see the information, namely three steps, about how the service works. The information is shown by three graphic pictures each of which depicts short explanation.

3.1.2.1  “Haz tu pedido” / “Make your order”
Here is a link in the text to the page to make an order
3.1.2.2  “Recogemos tu ropa” / “We pick up your clothes”
Elige en qué horario te acomoda e iremos al lugar que nos indiques a recoger tu ropa.
Choose what time it will fit you and we will come to the place that you has indicated for collecting your clothes.
3.1.2.3 “Ropa limpia en tus manos” / “Cleaned clothes in your hands”
 

3.1.3 “Ropa Limpia” / “Clean clothes”
The Washita-user can scroll down to this section after the section ”Fácil y rápido” / “Easy and fast”
This section is designed as more extensive explanation to “How the service works” and gives short answeres to FAQ and therefore, points out advantages of using Washita service.
Figure 3:
 
 
 
 
 
 
 
Olvídate de perder tiempo lavando o yendo a dejar y buscar tu ropa. DESCANSA! Nosotros nos hacemos cargo de tu ropa sucia
 
Forget about wasting time on doing laundry or going to laundry HAVE A REST! We’ll take care of your dirty clothes and linen
3.1.3.1 “Cuándo recogen la ropa sucia?” / “When is dirty laundry picked up?”
Todos los días, en el recorrido de la mañana o en el de la tarde.
Every day in the morning and in the afternoon.
3.1.3.2 “A qué hora son los recorridos?” / “At what time exactly?”
En la mañana entre las 8 a.m. y 10 a.m. y en la tarde entre las 4 p.m. y 6 p.m.
In the morning between 8 a.m. and 10 a.m., and in the afternoon between 4 p.m. and 6 p.m.
3.1.3.3 “Está disponible en mi comuna?” / “Is it available in my commune?“
Por el momento estamos en las siguientes comunas ver aquí.
 At the moment we are in the following communes see here. (here is the link to the section of the site Dónde está WASHita? / Where is washita?
3.1.3.4 “Si no estoy cuando pasen a recoger?” / “If I’m not available at the moment of picking up, when can it be collected?”
No te preocupes! Puedes dejarla en conserjería y nosotros la recogeremos. De lo contrario, puedes reagendar o pedir una devolución.
Do not worry! You can leave your laundry at concierge’s and we will pick it up. Otherwise, you can reschedule pick up time or request for refund.
 
3.1.3.5 “Cómo calcular el peso de mi ropa?” / “How to calculate the weight of my clothes?”
No es necesario que sea exacto! Sólo ingresa un valor aproximado y al recoger lo pesaremos bien. Si es menor te devolveremos la diferencia y si es mayor te solicitaremos el pago.
It doesn’t need to be exactly! Only enter an approximate value. The laundry will be weighed at our place after collection. If it is less, we will refund the difference, and if it is more, we will ask for payment.
 
3.1.3.6 “Cuándo llegará mi ropa limpia?” / “When will my clothes be ready?”
Tu ropa llegará en menos de 48 horas. Los retiros en horario PM se procesarán a contar del siguiente día hábil.
Your clothes will arrive in less than 48 hours. Withdrawals in PM hours will be processed from the next business day.
 
3.1.3.7 Tienes más preguntas? / “You have more questions?”
Escríbenos a contacto o al e-mail
Contact us (here is the link to section “Contacto” / Contacts”) or email us hola@washita.cl
 
3.1.4 “Dónde está WASHita?” / “Where is washita?”
This section can be reached by either further scrolling down or clicking tab “Dónde” as it is highlighted red in Figure 4.
Figure 4:
 
 
 
 
 
 
 
Si aún no aparecemos en tu comuna, escríbenos a contacto  y trataremos de habilitar la zona lo antes posible.
If we still do not appear in your commune, write to us and we will try to include the area as soon as possible.
 

3.1.5 “Precios” / “Price”
The Washita-user can  reach this section by either further scrolling down or clicking tab “Precios” as it is highlighted red in Figure 5.
Figure 5:
 
 
 
 
 
 
 
 
 
 
 
Here seeing prices, the user can select one of the two main services being provided by Washita: washing and drying, and ironing.

3.1.5.1 “Lavado y Doblado” / “Washing and drying”
The Washita-user can  reach this section by either clicking “Lavado y Doblado” / “Washing and drying” in the section “Precios” / “Price”or clicking the tab “LAVAR AHORA” / “WASH NOW”  as it is highlighted red in Figure 6.
Figure 6:
 
 
The Washita-user sees the price for 1 kg of laundry. He can increase the weight of laundry to have it washed and dried.
The user can tick off “Agregar planchado” / “Add ironing” to have his clothes ironed. In case of adding “ironing” as one more option of service, the user can type in kinds of items and their quantity to be ironed.
Figure 7:
 
 
 
 
 
 
The user can type in “Código Descuento” / “Discount code”.
As long as the user makes any changes in the left-hand side of the screen by changing the weight of laundry, adding ironing as one more service or using discount number, the price for the service changes at once, which can be examined in the right-hand of the screen.
Figure 8:
 
3.1.5.2 “Sólo planchado” / “Ironing only”
The Washita-user can  reach this section by either clicking “Sólo planchado” / “Ironing only” in the section “Precios” / “Price”or clicking the tab Sólo planchado” / “Ironing only” in the section “LAVAR AHORA” / “WASH NOW” as it is highlighted red in Figure 9.
Figure 9:
 
 
 
 
 
 
 
 
 
 
 
 
In the right-hand side of the screen, the Washita-user sees the price for 1 kg of laundry to have it ironed. The weight of laundry for ironing can be increased.
The option for hangers is set by default and therefore the price is included in the order summary.
If the user does not want to have his clothes hanged, he can choose the option to have clothes well folded. In this case the price for hangers is excluded from the order summary.
The user can type in “Código Descuento” / “Discount code”.
As long as the user makes any changes in the left-hand side of the screen by changing the weight of laundry for ironing, choosing to have clothes hanged or well folded, and/or using discount number, the price for the service changes at once, which can be examined in the right-hand of the screen.
3.1.5.3 “Lavaseco” / “Special cleaning”
The Washita-user can  reach this section by clicking the tab “Lavaseco” / “Special cleaning” in the section “LAVAR AHORA” / “WASH NOW” as it is highlighted red in Figure 10.
Figure 10:
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
In the left-hand side of the screen, the Washita-user can choose and set the quantity of items to be special or dry cleaned.
The user can type in “Código Descuento” / “Discount code”.
In the right-hand side of the screen the price for service changes as soon as the options for the service changes in the left-hand side of the screen.
3.1.5.4 “Hogar” / “Home items cleaning”
The Washita-user can  reach this section by clicking the tab “Lavaseco” / “Special cleaning” in the section “LAVAR AHORA” / “WASH NOW” as it is highlighted red in Figure 11.
Figure 11:
 
 
 
 
 
 
 
 
 
 
 
 
 
In the left-hand side of the screen, the Washita-user can choose and set the quantity of home items to be cleaned.
The user can type in “Código Descuento” / “Discount code”.
In the right-hand side of the screen the price for service changes as soon as the options for the service changes in the left-hand side of the screen.
3.1.5.5 User information
 
The second part of every of the four types of order is represented by entering information of the user: his name, town/city, address line, e-mail, whatsapp, dates of dispatch and delivery, the field for special request. This section can be reached by scrolling down after one of the service, i.e. it is the same for all the four types of services.


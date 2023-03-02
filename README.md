# scratchpad-ideas
mostly unformatted open source brainstorms🔮

## nestil, litsen, [other,..]

  <strong>any readers with knowledge and awareness of this goal already being acheived within existing technologies, please tell me! that is why i have shared my ~scratch~pad</strong> 
  <hr>

category: vulnerability scanning and attack prevention (ips)<br>
specificity: "eavesdropping attacks"<br>
purpose: to avoid single point of failure in vs/ips<br>
expanded:<br>

*<p>if there is failure of an attack prevention service at host level it can be assumed that clustering technology will allow for an alternate instance of the
    service to coninue operating. what if the prevention system failed entirely across all new instances. would there be any potential improvement by isolating         various prevention services (ie:attacks on IoT smart assistants, listening attacks on any internet device with listening capable hardware/software, data             harvesting attacks, etc..)</p>*
  
  caveats:
  - is this goal already acheived somehow in the services architecture (have not looked in detail on these scanning & prevention solutions recently)
  - if a future state becomes many separate services completing specific tasks, will resource effeciency be maintained in the process?
  
ecidence:<br>
https://www.fortinet.com/resources/cyberglossary/eavesdropping<br>
https://www.forbes.com/sites/zakdoffman/2020/10/07/fbi-drive-by-hacking-threat-gets-real-heres-why-you-should-be-concerned/?sh=410fd58a73d6<br>
https://threatpost.com/bug-iot-millions-devices-attackers-eavesdrop/168729/<br>

### pre-requisite

if aimed with specificity (home IoT devices for instance) it would require these home users/networks to implement scanning & prevention solutions. this is covered by my underlying project arguing for isp provided base security. in my ms final project i aim to suggest the practicality for isp's in partnership with open source security groups and government to deliver a reasonable baseline monitoring/alerting/prevention package included with all levels of internet service. paying for internet is a weak structure given our societial wealth distribution issues. as technology advances (especially in the open source ecosystem) we must not allow basic home security to come with such a price tag. 

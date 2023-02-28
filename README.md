# scratchpad-ideas🔮
mostly unformatted open source brainstorms

## nestil, litsen, [other,..]

category: vulnerability scanning and attack prevention (ips)<br>
specificity: "eavesdropping attacks"<br>
purpose: to avoid single point of failure in vs/ips<br>
expanded:<br>

*<p>if there is failure of an attack prevention service at host level it can be assumed that clustering technology will allow for an alternate instance of the
    service to coninue operating. what if the prevention system failed entirely across all new instances. would there be any potential improvement by isolating         various prevention services (ie:attacks on IoT smart assistants, listening attacks on any internet device with listening capable hardware/software, data             harvesting attacks, etc..)</p>*
  
  caveats:
  - is this goal already acheived somehow in the services architecture (have not looked in detail on these scanning & prevention solutions recently)
  - if a future state becomes many separate services completing specific tasks, will resource effeciency be maintained in the process?
  
  <strong>any readers with knowledge and awareness of this goal already being acheived within existing technologies, please tell me! that is why i have shared my ~scratch~pad</strong>

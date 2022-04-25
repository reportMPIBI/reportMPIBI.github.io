---
layout: default
---



# Gender Equality Officers
_If you want to report discrimination or harassment you can contact your local GEO. If you do not feel comfortable reaching out to a local person, you can also contact the Central Gender Equality office ._

- Max Planck Institute of Neurobiology (Martinsried)
	<ul>
	{% for member in site.data.members %}
		{% if member.position == "local GEO (MPIN)" %}
		  <li>
			<a href="mailto:{{ member.email }}">
			  {{ member.name }}
			</a>
			  ({{ member.lab }})
		  </li>
		  {% endif %}
		{% endfor %}
	</ul>

- Max Planck Institute of Ornithology (Seewiesen)
	<ul>
	{% for member in site.data.members %}
		{% if member.position == "local GEO (MPIO)" %}
		  <li>
			<a href="mailto:{{ member.email }}">
			  {{ member.name }}
			</a>
			  ({{ member.lab }})
		  </li>
		  {% endif %}
		{% endfor %}
	</ul>

- Central Gender Equality Officer
	<ul>
	{% for member in site.data.members %}
		{% if member.position == "central GEO" %}
		  <li>
			<a href="mailto:{{ member.email }}">
			  {{ member.name }}
			</a>
			  {{ member.lab }}
		  </li>
		  {% endif %}
		{% endfor %}
	</ul>

  

# Postdoc Representatives
_Postdoc or PhD students representatives can help you with any work-related issue_

- Max Planck Institute of Neurobiology (Martinsried)
  - [Postdocs representatives](mailto:postdoc-representatives@neuro.mpg.de)
  - Individual contacts:
	  - [Joseph Donovan](mailto:joe@bi.mpg.de) (Baier Lab)
	  - [Brad Edelman](mailto:bradley.edelman@bi.mpg.de) (Mace Lab)
	 
- Max Planck Institute of Ornithology (Seewiesen)
  - 

# PhD students Representatives

- Max Planck Institute of Neurobiology (Martinsried)
  - group email
  - Individual contacts:
	  - [Uwe Lewin](mailto:uwe.lewin@bi.mpg.de) (Bonhoeffer Lab)
	  - 
 
- Max Planck Institute of Ornithology (Seewiesen)
  - 

# Ombudsperson
_The Ombudsperson of your institute blablabla?





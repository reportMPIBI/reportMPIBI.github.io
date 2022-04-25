---
layout: default
---



# Gender Equality Officers
_If you want to report discrimination or harassment you can contact your local GEO. If you do not feel comfortable reaching out to a local person, you can also contact the Central Gender Equality office._

- Max Planck Institute of Neurobiology 
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
- Max Planck Institute of Ornithology 
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
_Postdoc or PhD students representatives can help you with work-related issues as a postdoc or a PhD student._

- Max Planck Institute of Neurobiology 
	<ul>
	{% for member in site.data.members %}
		{% if member.position == "postdoc rep" %}
		  <li>
			<a href="mailto:{{ member.email }}">
			  {{ member.name }}
			</a>
			  ({{ member.lab }})
		  </li>
		  {% endif %}
		{% endfor %}
	</ul>	 
- Max Planck Institute of Ornithology 
	<ul>
	{% for member in site.data.members %}
		{% if member.position == "postdoc rep (MPIO)" %}
		  <li>
			<a href="mailto:{{ member.email }}">
			  {{ member.name }}
			</a>
			  ({{ member.lab }})
		  </li>
		  {% endif %}
		{% endfor %}
	</ul>

# PhD students Representatives
- Max Planck Institute of Neurobiology 
	<ul>
	{% for member in site.data.members %}
		{% if member.position == "PhD rep" %}
		  <li>
			<a href="mailto:{{ member.email }}">
			  {{ member.name }}
			</a>
			  ({{ member.lab }})
		  </li>
		  {% endif %}
		{% endfor %}
	</ul>
- Max Planck Institute of Ornithology 
	<ul>
	{% for member in site.data.members %}
		{% if member.position == "PhD rep (MPIO)" %}
		  <li>
			<a href="mailto:{{ member.email }}">
			  {{ member.name }}
			</a>
			  ({{ member.lab }})
		  </li>
		  {% endif %}
		{% endfor %}
	</ul>

# Ombudsperson
_You can contact the Ombudsperson for questions and/or conflicts regarding good scientific practice._

- Max Planck Institute of Neurobiology 
	<ul>
	{% for member in site.data.members %}
		{% if member.position == "ombudsperson" %}
		  <li>
			<a href="mailto:{{ member.email }}">
			  {{ member.name }}
			</a>
			  ({{ member.lab }})
		  </li>
		  {% endif %}
		{% endfor %}
	</ul>



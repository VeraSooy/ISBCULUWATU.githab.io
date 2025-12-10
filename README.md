# ISBCULUWATU.githab.io
my project 
">Message us</a>
            <p class="note" style="margin-top:8px">Replace with your real number.</p>
          </div>
        </div>
        <div class="card">
          <div class="body">
            <div class="pill">Instagram</div>
            <p>Daily vibes, stories, and community moments.</p>
            <a class="btn" target="_blank" rel="noopener" href="https://instagram.com/yourhandle">Follow</a>
            <p class="note" style="margin-top:8px">Replace link with your IG handle.</p>
          </div>
        </div>
        <div class="card">
          <div class="body">
            <div class="pill">Email</div>
            <p>Partnerships, events, private sessions.</p>
            <a class="btn" href="mailto:hello@isbc-uluwatu.com">hello@isbc-uluwatu.com</a>
            <p class="note" style="margin-top:8px">Update to your email if different.</p>
          </div>
        </div>
      </div>

      <p class="note" style="margin-top:12px">
        Bring gloves and wraps if you have them. Limited gear available on site.
      </p>
    </div>
  </section>

  <footer>
    <div class="container foot">
      <div>© <span id="y"></span> ISBC ULUWATU — All rights reserved.</div>
      <div class="note">Open-air combat sports gym • Uluwatu, Bali</div>
    </div>
  </footer>

  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"SportsActivityLocation",
    "name":"ISBC ULUWATU",
    "description":"Open-air boxing and combat sports with a positive community in Uluwatu, Bali.",
    "address":{
      "@type":"PostalAddress",
      "streetAddress":"Jl. Labuansait, Pecatu, Kec. Kuta Sel.",
      "addressLocality":"Kabupaten Badung",
      "addressRegion":"Bali",
      "postalCode":"80361",
      "addressCountry":"ID"
    },
    "geo":{
      "@type":"GeoCoordinates",
      "latitude":-8.806,
      "longitude":115.104
    },
    "amenityFeature":[
      {"@type":"LocationFeatureSpecification","name":"Open-air training","value":true},
      {"@type":"LocationFeatureSpecification","name":"Ice baths","value":true},
      {"@type":"LocationFeatureSpecification","name":"Community runs","value":true}
    ],
    "sameAs":[
      "https://instagram.com/yourhandle"
    ]
  }
  </script>

  <script>
    // Year
    document.getElementById('y').textContent=new Date().getFullYear();

    // Smooth scroll
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click',e=>{
        const id=a.getAttribute('href').slice(1);
        const el=document.getElementById(id);
        if(el){e.preventDefault();el.scrollIntoView({behavior:'smooth',block:'start'})}
      })
    });

    // Mobile menu toggle
    const btn=document.getElementById('menuBtn');
    const menu=document.getElementById('mobileMenu');
    btn&&btn.addEventListener('click',()=>menu.classList.toggle('open'));
    menu&&menu.querySelectorAll('a').forEach(l=>l.addEventListener('click',()=>menu.classList.remove('open')));
  </script>
</body>
</html>

export default function ApexReachLandingPage() {
  return (
    <div className="min-h-screen bg-black text-white font-sans">
      {/* Hero Section */}
      <section className="relative overflow-hidden px-6 py-24 md:px-16 lg:px-32">
        <div className="absolute inset-0 bg-gradient-to-br from-zinc-900 via-black to-zinc-950 opacity-90" />

        <div className="relative z-10 max-w-6xl mx-auto grid lg:grid-cols-2 gap-16 items-center">
          <div>
            <p className="uppercase tracking-[0.3em] text-sm text-zinc-400 mb-6">
              ApexReach Marketing Agency
            </p>

            <h1 className="text-5xl md:text-7xl font-bold leading-tight mb-6">
              We Don’t Run Ads.
              <span className="block text-zinc-300">
                We Build Machines That Print Clients.
              </span>
            </h1>

            <p className="text-lg text-zinc-400 max-w-xl mb-10 leading-relaxed">
              ApexReach helps local and luxury businesses scale through high-converting Meta & Google Ads systems designed to generate leads, sales, and consistent growth.
            </p>

            <div className="flex flex-col sm:flex-row gap-4">
              <button className="bg-white text-black px-8 py-4 rounded-2xl font-semibold hover:scale-105 transition duration-300">
                Book Free Strategy Call
              </button>

              <button className="border border-zinc-700 px-8 py-4 rounded-2xl hover:bg-zinc-900 transition duration-300">
                View Results
              </button>
            </div>
          </div>

          <div className="grid grid-cols-2 gap-5">
            <div className="bg-zinc-900 border border-zinc-800 p-8 rounded-3xl shadow-2xl">
              <h3 className="text-4xl font-bold mb-2">R12M+</h3>
              <p className="text-zinc-400">Revenue Generated</p>
            </div>

            <div className="bg-zinc-900 border border-zinc-800 p-8 rounded-3xl shadow-2xl">
              <h3 className="text-4xl font-bold mb-2">3.2x</h3>
              <p className="text-zinc-400">Average ROAS</p>
            </div>

            <div className="bg-zinc-900 border border-zinc-800 p-8 rounded-3xl shadow-2xl">
              <h3 className="text-4xl font-bold mb-2">100+</h3>
              <p className="text-zinc-400">Campaigns Managed</p>
            </div>

            <div className="bg-zinc-900 border border-zinc-800 p-8 rounded-3xl shadow-2xl">
              <h3 className="text-4xl font-bold mb-2">24/7</h3>
              <p className="text-zinc-400">Optimization Focus</p>
            </div>
          </div>
        </div>
      </section>

      {/* Services */}
      <section className="px-6 py-24 md:px-16 lg:px-32 border-t border-zinc-900">
        <div className="max-w-6xl mx-auto">
          <div className="mb-16">
            <p className="uppercase tracking-[0.3em] text-sm text-zinc-500 mb-4">
              Services
            </p>

            <h2 className="text-4xl md:text-5xl font-bold max-w-3xl leading-tight">
              Growth Systems Built For Businesses Ready To Scale.
            </h2>
          </div>

          <div className="grid md:grid-cols-3 gap-6">
            {[
              {
                title: 'Meta Ads',
                description:
                  'High-converting Facebook & Instagram ad campaigns focused on leads, sales, and customer acquisition.',
              },
              {
                title: 'Google Ads',
                description:
                  'Search campaigns designed to capture high-intent buyers actively searching for your service.',
              },
              {
                title: 'Lead Generation Systems',
                description:
                  'Funnels and conversion systems engineered to turn clicks into paying customers.',
              },
            ].map((service, index) => (
              <div
                key={index}
                className="bg-zinc-950 border border-zinc-800 rounded-3xl p-8 hover:border-zinc-600 transition duration-300"
              >
                <h3 className="text-2xl font-semibold mb-4">{service.title}</h3>
                <p className="text-zinc-400 leading-relaxed">
                  {service.description}
                </p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Niches */}
      <section className="px-6 py-24 md:px-16 lg:px-32 border-t border-zinc-900 bg-zinc-950/40">
        <div className="max-w-6xl mx-auto text-center">
          <p className="uppercase tracking-[0.3em] text-sm text-zinc-500 mb-4">
            Who We Work With
          </p>

          <h2 className="text-4xl md:text-5xl font-bold mb-14">
            Built For High-Value Businesses.
          </h2>

          <div className="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
            {[
              'Real Estate Agencies',
              'Luxury Car Businesses',
              'Aesthetic Clinics',
              'Premium Service Brands',
            ].map((item, index) => (
              <div
                key={index}
                className="border border-zinc-800 rounded-2xl py-10 px-6 bg-black"
              >
                <p className="text-lg font-medium">{item}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Why Choose Us */}
      <section className="px-6 py-24 md:px-16 lg:px-32 border-t border-zinc-900">
        <div className="max-w-6xl mx-auto grid lg:grid-cols-2 gap-16 items-center">
          <div>
            <p className="uppercase tracking-[0.3em] text-sm text-zinc-500 mb-4">
              Why ApexReach
            </p>

            <h2 className="text-4xl md:text-5xl font-bold leading-tight mb-8">
              We Focus On Revenue, Not Vanity Metrics.
            </h2>

            <p className="text-zinc-400 text-lg leading-relaxed">
              Most agencies focus on impressions and clicks. ApexReach focuses on one thing: measurable business growth. Every campaign is designed with strategy, data, and conversion psychology to maximize ROI.
            </p>
          </div>

          <div className="space-y-6">
            {[
              'Data-driven campaign optimization',
              'Premium brand positioning',
              'Fast communication & reporting',
              'Scalable lead generation systems',
            ].map((point, index) => (
              <div
                key={index}
                className="bg-zinc-950 border border-zinc-800 rounded-2xl p-6"
              >
                <p className="text-lg">✓ {point}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* CTA */}
      <section className="px-6 py-24 md:px-16 lg:px-32 border-t border-zinc-900">
        <div className="max-w-4xl mx-auto text-center bg-zinc-950 border border-zinc-800 rounded-[2rem] p-12 md:p-20 shadow-2xl">
          <p className="uppercase tracking-[0.3em] text-sm text-zinc-500 mb-4">
            Ready To Scale?
          </p>

          <h2 className="text-4xl md:text-6xl font-bold mb-6 leading-tight">
            Let’s Build Your Client Acquisition Machine.
          </h2>

          <p className="text-zinc-400 text-lg mb-10 max-w-2xl mx-auto">
            Book a free strategy call and discover how ApexReach can help your business generate more leads, customers, and revenue through strategic paid advertising.
          </p>

          <button className="bg-white text-black px-10 py-5 rounded-2xl text-lg font-semibold hover:scale-105 transition duration-300">
            Book Free Strategy Call
          </button>
        </div>
      </section>
    </div>
  )
}
# apexreach-landing-page-1

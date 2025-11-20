export default function CivitanoLanding() {
  return (
    <div className="font-sans bg-white text-gray-900">
      {/* Hero Section */}
      <header className="absolute top-0 left-0 w-full z-20 flex justify-between items-center px-8 py-6">
          <img src="https://civitano-berlin.de/wp-content/uploads/2022/08/civitano-logo.svg" alt="CIVITANO Logo" className="h-10 md:h-12" />
        </header>
        <section className="relative h-[85vh] flex items-center justify-center bg-cover bg-center" style={{backgroundImage: "url('/mnt/data/Fassadenansicht.jpg')"}}>
        <div className="absolute inset-0 bg-black/50"></div>
        <div className="relative z-10 max-w-4xl mx-auto px-6 text-center text-white">
          <h1 className="text-4xl md:text-6xl font-light tracking-wide mb-6">CIVITANO – Neues Wohnen in Berlin-Britz</h1>
          <p className="text-lg md:text-2xl font-light mb-8">2–4 Zimmer Eigentumswohnungen • Exklusive Gartenwohnung • Bauhaus-Architektur</p>
          <div className="flex flex-col md:flex-row gap-4 justify-center">
            <button className="px-8 py-4 bg-white text-gray-900 text-sm uppercase tracking-wide shadow-lg hover:bg-gray-200 transition">Exposé anfordern</button>
            <button className="px-8 py-4 border border-white text-white text-sm uppercase tracking-wide hover:bg-white/10 transition">Beratung sichern</button>
          </div>
        </div>
      </section>

      {/* Gallery Section */}
      <section className="py-20 max-w-6xl mx-auto px-6">
        <div className="grid grid-cols-1 md:grid-cols-3 gap-6">
          <img src="/mnt/data/WE04.jpg" alt="Innenansicht" className="rounded-lg shadow-md object-cover h-72 w-full" />
          <img src="/mnt/data/WE05.jpg" alt="Innenansicht" className="rounded-lg shadow-md object-cover h-72 w-full" />
          <img src="/mnt/data/Hofseite.jpg" alt="Hofseite" className="rounded-lg shadow-md object-cover h-72 w-full" />
        </div>
      </section>

      {/* Highlights Section */}
      <section className="py-20 max-w-6xl mx-auto px-6 text-center">
        <h2 className="text-3xl font-light mb-6">Zeitlose Architektur. Berliner Persönlichkeit.</h2>
        <p className="text-lg text-gray-700 max-w-3xl mx-auto mb-12">Mit CIVITANO entstehen hochwertige Neubauwohnungen mitten in Berlin-Britz – moderne Architektur, harmonische Wohnatmosphäre und solide Bauqualität für Eigennutzer und Kapitalanleger.</p>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div className="p-6 border rounded-lg shadow-sm">2–4 Zimmer Wohnungen</div>
          <div className="p-6 border rounded-lg shadow-sm">Garten- & Balkonwohnungen</div>
          <div className="p-6 border rounded-lg shadow-sm">Tiefgarage & Aufzug</div>
        </div>
      </section>

      {/* Partner Band */}
      <section className="py-6 bg-[#f3eee7]">
        <div className="max-w-6xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-4">
          <p className="text-sm text-gray-700">Ein Projekt von <span className="font-medium">Baywobau</span> · Im Vertrieb durch <span className="font-medium">CENTA GmbH</span></p>
        </div>
      </section>

      {/* Grundrisse Section */}
      <section id="grundrisse" className="py-20 max-w-6xl mx-auto px-6">
        <h2 className="text-3xl font-light text-center mb-10">Ausgewählte Grundrisse</h2>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-10">
          <div className="border rounded-lg p-6 shadow-sm bg-white">
            <h4 className="text-lg font-light mb-4">WE 06 – 4-Zimmer Wohnung</h4>
            <a href="/mnt/data/civitano_Grundriss_WE06.pdf" target="_blank" className="block text-blue-700 underline mb-4">Grundriss ansehen (PDF)</a>
          </div>
          <div className="border rounded-lg p-6 shadow-sm bg-white">
            <h4 className="text-lg font-light mb-4">WE 07 – 2-Zimmer Wohnung</h4>
            <a href="/mnt/data/civitano_Grundriss_WE07.pdf" target="_blank" className="block text-blue-700 underline mb-4">Grundriss ansehen (PDF)</a>
          </div>
          <div className="border rounded-lg p-6 shadow-sm bg-white">
            <h4 className="text-lg font-light mb-4">WE 08 – 3-Zimmer Wohnung</h4>
            <a href="/mnt/data/civitano_Grundriss_WE08.pdf" target="_blank" className="block text-blue-700 underline mb-4">Grundriss ansehen (PDF)</a>
          </div>
          <div className="border rounded-lg p-6 shadow-sm bg-white">
            <h4 className="text-lg font-light mb-4">WE 09 – 3,5-Zimmer Wohnung</h4>
            <a href="/mnt/data/civitano_Grundriss_WE09.pdf" target="_blank" className="block text-blue-700 underline mb-4">Grundriss ansehen (PDF)</a>
          </div>
        </div>
      </section>

      {/* CTA Section */}
      <section id="kontakt" className="py-20 bg-gray-100">
        <div className="max-w-3xl mx-auto px-6">
          <h3 className="text-2xl font-light mb-2 text-center">Jetzt Exposé erhalten</h3>
          <p className="text-gray-700 mb-8 text-center">Wir senden Ihnen Grundrisse, Lagepläne und Details per E-Mail. Unverbindlich & datenschutzkonform.</p>
          <form className="grid grid-cols-1 gap-4 bg-white p-6 rounded-xl shadow">
            <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
              <input className="border p-3 rounded" placeholder="Vorname" />
              <input className="border p-3 rounded" placeholder="Nachname" />
            </div>
            <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
              <input type="email" className="border p-3 rounded" placeholder="E-Mail*" required />
              <input className="border p-3 rounded" placeholder="Telefon*" required />
            </div>
            <select className="border p-3 rounded">
              <option>Ich bin Eigennutzer</option>
              <option>Ich bin Kapitalanleger</option>
            </select>
            <textarea className="border p-3 rounded min-h-[120px]" placeholder="Ihre Nachricht"></textarea>
            <button className="px-8 py-4 bg-gray-900 text-white uppercase tracking-wide text-sm rounded hover:opacity-90">Exposé anfordern</button>
            <p className="text-xs text-gray-500 text-center">Mit Klick auf "Exposé anfordern" stimmen Sie der Kontaktaufnahme durch die CENTA GmbH zu.</p>
          </form>
        </div>
      </section>
    </div>
  );
}

# Chetanpatil-portfolioexport default function Portfolio() { return ( <div className="min-h-screen bg-white text-gray-900 font-sans"> <header className="bg-gradient-to-r from-blue-600 to-indigo-600 text-white p-6 shadow-md"> <h1 className="text-4xl font-bold">Chetan Patil</h1> <p className="text-lg">Senior Data Analyst | Ex-Deloitte | Founder of Novaritz</p> </header>

<main className="p-6 max-w-5xl mx-auto">
    {/* About Section */}
    <section className="my-12">
      <h2 className="text-2xl font-semibold mb-4">About Me</h2>
      <p>
        I’m a highly motivated data professional with 3+ years of experience at Deloitte Consulting, specializing in transforming business data into actionable insights. As the founder of Novaritz, I aim to provide freelance job opportunities to talented individuals from small towns.
      </p>
    </section>

    {/* Experience Section */}
    <section className="my-12">
      <h2 className="text-2xl font-semibold mb-4">Experience</h2>
      <div className="bg-gray-100 p-4 rounded shadow">
        <h3 className="text-xl font-bold">Deloitte Consulting India Pvt Ltd</h3>
        <p className="text-sm text-gray-700">Senior Data Analyst (Jan 2023 – June 2025)</p>
        <ul className="list-disc list-inside mt-2 space-y-1">
          <li>Developed dashboards using Tableau and Power BI</li>
          <li>Built ML models for business predictions</li>
          <li>Worked with AWS and Azure cloud environments</li>
          <li>Collaborated with teams to deliver analytics solutions</li>
        </ul>
      </div>
    </section>

    {/* Skills Section */}
    <section className="my-12">
      <h2 className="text-2xl font-semibold mb-4">Skills & Tools</h2>
      <div className="grid grid-cols-2 sm:grid-cols-3 gap-4">
        {['Tableau', 'Power BI', 'Python', 'SQL', 'AWS', 'Azure', 'Machine Learning', 'AI', 'Excel', 'Git'].map(skill => (
          <span key={skill} className="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm">{skill}</span>
        ))}
      </div>
    </section>

    {/* Projects Section */}
    <section className="my-12">
      <h2 className="text-2xl font-semibold mb-4">Projects</h2>
      <ul className="space-y-4">
        <li>
          <strong>Sales Forecasting Model</strong> – Built a predictive model to estimate next quarter sales using Python.
        </li>
        <li>
          <strong>Customer Churn Dashboard</strong> – Developed interactive Tableau dashboard for churn analysis.
        </li>
        <li>
          <strong>Remote Work Tracker</strong> – Created a Power BI report to monitor productivity of remote employees.
        </li>
      </ul>
    </section>

    {/* Certifications Section */}
    <section className="my-12">
      <h2 className="text-2xl font-semibold mb-4">Certifications</h2>
      <ul className="list-disc list-inside">
        <li>AWS Certified Solutions Architect – Associate</li>
        <li>Microsoft Azure Fundamentals</li>
        <li>Tableau Desktop Specialist</li>
        <li>Machine Learning Specialization – Coursera</li>
      </ul>
    </section>

    {/* Contact Section */}
    <section className="my-12">
      <h2 className="text-2xl font-semibold mb-4">Contact</h2>
      <p>Email: <a href="mailto:patilchetan545@gmail.com" className="text-blue-600">patilchetan545@gmail.com</a></p>
      <p>Phone: +91 9588695132</p>
      <p>LinkedIn: <a href="#" className="text-blue-600">linkedin.com/in/chetanpatil</a></p>
      <p>Website: <a href="#" className="text-blue-600">novaritz.com</a></p>
    </section>
  </main>

  <footer className="text-center text-sm text-gray-600 py-6 border-t">
    © {new Date().getFullYear()} Chetan Patil. All rights reserved.
  </footer>
</div>

); }

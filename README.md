export default function JavarResumePortfolio() {
  const experiences = [
    {
      title: 'Structural Drafter / AutoCAD Technical II',
      company: 'CTIPilipinas, Inc.',
      date: 'Nov 2024 – Present',
      details: [
        'Preparation of structural plans for infrastructure projects',
        'DPWH-compliant drafting and detailing',
        'Structural coordination and drawing revisions'
      ]
    },
    {
      title: 'Project Engineer',
      company: 'Newington Builder Inc.',
      date: 'Aug 2023 – Nov 2024',
      details: [
        'Managed flood control infrastructure projects',
        'Site supervision and manpower coordination',
        'QA/QC inspection and progress monitoring'
      ]
    },
    {
      title: 'Civil Engineer',
      company: 'JQ International Construction Inc.',
      date: 'Jul 2022 – Aug 2023',
      details: [
        'QA/QC for high-rise residential projects',
        'Quantity Surveying and Cost Estimation',
        'Bar Bending Schedule (BBS) preparation'
      ]
    },
    {
      title: 'Rebar Engineer',
      company: 'Coogee International Development Inc.',
      date: 'Aug 2019 – Jan 2022',
      details: [
        'Rebar optimization and quantity estimation',
        'Reinforcement detailing and cutting lists',
        'Material waste reduction planning'
      ]
    }
  ];

  const skills = [
    'AutoCAD 2D/3D',
    'Structural Detailing',
    'Quantity Surveying',
    'Cost Estimation',
    'QA/QC Inspection',
    'Project Engineering',
    'Procore',
    'SketchUp',
    'BBS Preparation',
    'DPWH Standards'
  ];

  const certifications = [
    'Advanced Occupational Safety and Health (SO3)',
    'Construction Occupational Safety and Health (SO2)',
    'Procore Certified Engineer',
    'AutoCAD Drafting & Design',
    'Training of Trainers (TOT)',
    'Computer Hardware Servicing NCII'
  ];

  return (
    <div className="min-h-screen bg-slate-100 p-6 md:p-12">
      <div className="max-w-6xl mx-auto bg-white shadow-2xl rounded-3xl overflow-hidden grid md:grid-cols-3">
        {/* Sidebar */}
        <div className="bg-slate-900 text-white p-8">
          <div className="text-center">
            <div className="w-32 h-32 mx-auto rounded-full bg-slate-700 flex items-center justify-center text-4xl font-bold mb-4">
              JC
            </div>
            <h1 className="text-3xl font-bold">Javar Cosain</h1>
            <p className="text-slate-300 mt-2 text-sm">
              Senior Civil Engineering Associate
            </p>
          </div>

          <div className="mt-10 space-y-6">
            <div>
              <h2 className="text-xl font-semibold border-b border-slate-700 pb-2 mb-3">
                Contact
              </h2>
              <div className="space-y-2 text-sm text-slate-300">
                <p>📍 Quezon City, Philippines</p>
                <p>📞 +63 954 255 9235</p>
                <p>📧 javar.cosain.civil@gmail.com</p>
              </div>
            </div>

            <div>
              <h2 className="text-xl font-semibold border-b border-slate-700 pb-2 mb-3">
                Skills
              </h2>
              <div className="flex flex-wrap gap-2">
                {skills.map((skill, index) => (
                  <span
                    key={index}
                    className="bg-slate-700 px-3 py-1 rounded-full text-xs"
                  >
                    {skill}
                  </span>
                ))}
              </div>
            </div>

            <div>
              <h2 className="text-xl font-semibold border-b border-slate-700 pb-2 mb-3">
                Certifications
              </h2>
              <ul className="space-y-2 text-sm text-slate-300 list-disc pl-5">
                {certifications.map((cert, index) => (
                  <li key={index}>{cert}</li>
                ))}
              </ul>
            </div>

            <div>
              <h2 className="text-xl font-semibold border-b border-slate-700 pb-2 mb-3">
                Education
              </h2>
              <p className="text-sm text-slate-300">
                Bachelor of Science in Civil Engineering
              </p>
              <p className="text-xs text-slate-400">2014 – 2018</p>
            </div>
          </div>
        </div>

        {/* Main Content */}
        <div className="md:col-span-2 p-8 md:p-10">
          <section>
            <h2 className="text-3xl font-bold text-slate-800 mb-4">
              Professional Summary
            </h2>
            <p className="text-slate-600 leading-8 text-justify">
              Highly proficient Civil Engineering Professional with 10+ years of
              combined experience in structural detailing, construction
              coordination, QA/QC inspection, quantity surveying, and project
              engineering. Experienced in handling high-rise residential,
              infrastructure, bridge, and flood control projects while ensuring
              technical accuracy, constructability, and compliance with DPWH
              standards.
            </p>
          </section>

          <section className="mt-10">
            <h2 className="text-3xl font-bold text-slate-800 mb-6">
              Professional Experience
            </h2>

            <div className="space-y-8">
              {experiences.map((exp, index) => (
                <div
                  key={index}
                  className="border-l-4 border-slate-800 pl-6"
                >
                  <div className="flex flex-col md:flex-row md:items-center md:justify-between">
                    <div>
                      <h3 className="text-xl font-semibold text-slate-800">
                        {exp.title}
                      </h3>
                      <p className="text-slate-600 font-medium">
                        {exp.company}
                      </p>
                    </div>
                    <span className="text-sm text-slate-500 mt-2 md:mt-0">
                      {exp.date}
                    </span>
                  </div>

                  <ul className="mt-4 space-y-2 text-slate-600 list-disc pl-5">
                    {exp.details.map((detail, idx) => (
                      <li key={idx}>{detail}</li>
                    ))}
                  </ul>
                </div>
              ))}
            </div>
          </section>

          <section className="mt-10 grid md:grid-cols-2 gap-6">
            <div className="bg-slate-100 rounded-2xl p-6">
              <h3 className="text-2xl font-bold text-slate-800 mb-4">
                Engineering Expertise
              </h3>
              <ul className="space-y-3 text-slate-600">
                <li>✔ Structural Detailing</li>
                <li>✔ Quantity Surveying</li>
                <li>✔ Cost Estimation</li>
                <li>✔ QA/QC Inspection</li>
                <li>✔ Construction Coordination</li>
              </ul>
            </div>

            <div className="bg-slate-100 rounded-2xl p-6">
              <h3 className="text-2xl font-bold text-slate-800 mb-4">
                Software & Tools
              </h3>
              <ul className="space-y-3 text-slate-600">
                <li>✔ AutoCAD 2D/3D</li>
                <li>✔ Procore</li>
                <li>✔ SketchUp</li>
                <li>✔ Microsoft Excel</li>
                <li>✔ DPWH Standards</li>
              </ul>
            </div>
          </section>

          <section className="mt-10 bg-slate-900 text-white rounded-3xl p-8">
            <h2 className="text-3xl font-bold mb-4">Career Objective</h2>
            <p className="leading-8 text-slate-300">
              To contribute technical expertise in structural detailing,
              project engineering, and construction management while supporting
              efficient, safe, and high-quality project execution for local and
              international engineering projects.
            </p>
          </section>
        </div>
      </div>
    </div>
  );
}

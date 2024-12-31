# Quantum computing

---

اللَّهُمَّ لا سَهْلَ إِلَّا مَا جَعَلْتَهُ سَهْلًا، وَأَنْتَ تَجْعَلُ الصَّعْبَ إِذَا شِئْتَ سَهْلًا

---

has always been a field I’ve wanted to explore. despite the circumstances, studies and i know these are just execuses i didn't started early.
However, incha’Allah, we’re determined to give our best effort and learn as much as possible in the future."

---

<h1>Path</h1>

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Markmap</title>
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      #mindmap {
        display: block;
        width: 100vw;
        height: 100vh;
      }
    </style>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/markmap-toolbar@0.18.3/dist/style.css"
    />
  </head>
  <body>
    <svg id="mindmap"></svg>
    <script src="https://cdn.jsdelivr.net/npm/d3@7.9.0/dist/d3.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/markmap-view@0.18.3/dist/browser/index.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/markmap-toolbar@0.18.3/dist/index.js"></script>
    <script>
      (() => {
        setTimeout(() => {
          const { markmap: k, mm: q } = window,
            A = new k.Toolbar();
          A.attach(q);
          const D = A.render();
          D.setAttribute("style", "position:absolute;bottom:20px;right:20px"),
            document.body.append(D);
        });
      })();
    </script>
    <script>
      ((n, P, F, I) => {
        const V = n();
        window.mm = V.Markmap.create(
          "svg#mindmap",
          (P || V.deriveOptions)(I),
          F
        );
      })(
        () => window.markmap,
        null,
        {
          content: "Quantum Computing Learning Path",
          children: [
            {
              content: "1. Foundation",
              children: [
                {
                  content: "1.1 Mathematics",
                  children: [
                    {
                      content:
                        "Linear Algebra",
                      children: [
                        {
                          content: "Vectors and Matrices",
                          children: [],
                          payload: { tag: "li", lines: "5,6" },
                        },
                        {
                          content: "Eigenvalues and Eigenvectors",
                          children: [],
                          payload: { tag: "li", lines: "6,7" },
                        },
                        {
                          content: "Tensor Products",
                          children: [],
                          payload: { tag: "li", lines: "7,8" },
                        },
                        {
                          content: "Unitary and Hermitian Matrices",
                          children: [],
                          payload: { tag: "li", lines: "8,9" },
                        },
                      ],
                      payload: { tag: "li", lines: "4,9" },
                    },
                    {
                      content: "Probability and Statistics",
                      children: [
                        {
                          content: "Probabilities and Distributions",
                          children: [],
                          payload: { tag: "li", lines: "10,11" },
                        },
                        {
                          content: "Expectation Values",
                          children: [],
                          payload: { tag: "li", lines: "11,12" },
                        },
                        {
                          content: "Measurement Theory",
                          children: [],
                          payload: { tag: "li", lines: "12,13" },
                        },
                      ],
                      payload: { tag: "li", lines: "9,13" },
                    },
                    {
                      content: "Complex Numbers",
                      children: [
                        {
                          content: "Basics of Complex Arithmetic",
                          children: [],
                          payload: { tag: "li", lines: "14,15" },
                        },
                        {
                          content: "Complex Conjugate and Modulus",
                          children: [],
                          payload: { tag: "li", lines: "15,16" },
                        },
                      ],
                      payload: { tag: "li", lines: "13,16" },
                    },
                    {
                      content: "Group Theory (Optional)",
                      children: [
                        {
                          content: "Symmetries in Quantum Systems",
                          children: [],
                          payload: { tag: "li", lines: "17,19" },
                        },
                      ],
                      payload: { tag: "li", lines: "16,19" },
                    },
                  ],
                  payload: { tag: "h3", lines: "3,4" },
                },
                {
                  content: "1.2 Quantum Mechanics",
                  children: [
                    {
                      content: "Quantum States",
                      children: [
                        {
                          content: "Superposition",
                          children: [],
                          payload: { tag: "li", lines: "21,22" },
                        },
                        {
                          content: "Entanglement",
                          children: [],
                          payload: { tag: "li", lines: "22,23" },
                        },
                      ],
                      payload: { tag: "li", lines: "20,23" },
                    },
                    {
                      content: "Quantum Operators",
                      children: [
                        {
                          content: "Observables",
                          children: [],
                          payload: { tag: "li", lines: "24,25" },
                        },
                        {
                          content: "Unitary Operators",
                          children: [],
                          payload: { tag: "li", lines: "25,26" },
                        },
                      ],
                      payload: { tag: "li", lines: "23,26" },
                    },
                    {
                      content: "Measurement and Probabilistic Outcomes",
                      children: [],
                      payload: { tag: "li", lines: "26,27" },
                    },
                    {
                      content: "Wavefunction and State Collapse",
                      children: [],
                      payload: { tag: "li", lines: "27,29" },
                    },
                  ],
                  payload: { tag: "h3", lines: "19,20" },
                },
                {
                  content: "1.3 Computer Science Basics",
                  children: [
                    {
                      content: "Programming",
                      children: [
                        {
                          content: "Python",
                          children: [],
                          payload: { tag: "li", lines: "31,32" },
                        },
                        {
                          content: "Git and Version Control",
                          children: [],
                          payload: { tag: "li", lines: "32,33" },
                        },
                      ],
                      payload: { tag: "li", lines: "30,33" },
                    },
                    {
                      content: "Classical Algorithms",
                      children: [
                        {
                          content: "Sorting and Searching",
                          children: [],
                          payload: { tag: "li", lines: "34,35" },
                        },
                        {
                          content: "Graph Algorithms",
                          children: [],
                          payload: { tag: "li", lines: "35,36" },
                        },
                      ],
                      payload: { tag: "li", lines: "33,36" },
                    },
                    {
                      content: "Computational Complexity",
                      children: [
                        {
                          content: "P, NP, and BQP",
                          children: [],
                          payload: { tag: "li", lines: "37,39" },
                        },
                      ],
                      payload: { tag: "li", lines: "36,39" },
                    },
                  ],
                  payload: { tag: "h3", lines: "29,30" },
                },
              ],
              payload: { tag: "h2", lines: "2,3" },
            },
            {
              content: "2. Quantum Computing Basics",
              children: [
                {
                  content: "2.1 Concepts",
                  children: [
                    {
                      content: "Qubits",
                      children: [
                        {
                          content: "Bloch Sphere Representation",
                          children: [],
                          payload: { tag: "li", lines: "42,43" },
                        },
                      ],
                      payload: { tag: "li", lines: "41,43" },
                    },
                    {
                      content: "Quantum Gates",
                      children: [
                        {
                          content: "Single-Qubit Gates (Hadamard, Pauli-X)",
                          children: [],
                          payload: { tag: "li", lines: "44,45" },
                        },
                        {
                          content: "Multi-Qubit Gates (CNOT, SWAP)",
                          children: [],
                          payload: { tag: "li", lines: "45,46" },
                        },
                      ],
                      payload: { tag: "li", lines: "43,46" },
                    },
                    {
                      content: "Quantum Circuits",
                      children: [
                        {
                          content: "Circuit Design and Representation",
                          children: [],
                          payload: { tag: "li", lines: "47,48" },
                        },
                        {
                          content: "Measurement",
                          children: [],
                          payload: { tag: "li", lines: "48,50" },
                        },
                      ],
                      payload: { tag: "li", lines: "46,50" },
                    },
                  ],
                  payload: { tag: "h3", lines: "40,41" },
                },
                {
                  content: "2.2 Quantum Algorithms",
                  children: [
                    {
                      content: "Grover's Algorithm",
                      children: [
                        {
                          content: "Database Search",
                          children: [],
                          payload: { tag: "li", lines: "52,53" },
                        },
                      ],
                      payload: { tag: "li", lines: "51,53" },
                    },
                    {
                      content: "Shor's Algorithm",
                      children: [
                        {
                          content: "Factoring Integers",
                          children: [],
                          payload: { tag: "li", lines: "54,55" },
                        },
                      ],
                      payload: { tag: "li", lines: "53,55" },
                    },
                    {
                      content: "Quantum Fourier Transform",
                      children: [
                        {
                          content: "Period Finding",
                          children: [],
                          payload: { tag: "li", lines: "56,58" },
                        },
                      ],
                      payload: { tag: "li", lines: "55,58" },
                    },
                  ],
                  payload: { tag: "h3", lines: "50,51" },
                },
                {
                  content: "2.3 Quantum Error Correction",
                  children: [
                    {
                      content: "Decoherence and Noise",
                      children: [],
                      payload: { tag: "li", lines: "59,60" },
                    },
                    {
                      content: "Error-Correcting Codes",
                      children: [
                        {
                          content: "Shor Code",
                          children: [],
                          payload: { tag: "li", lines: "61,62" },
                        },
                        {
                          content: "Surface Code",
                          children: [],
                          payload: { tag: "li", lines: "62,64" },
                        },
                      ],
                      payload: { tag: "li", lines: "60,64" },
                    },
                  ],
                  payload: { tag: "h3", lines: "58,59" },
                },
              ],
              payload: { tag: "h2", lines: "39,40" },
            },
            {
              content: "3. Programming Frameworks",
              children: [
                {
                  content: "3.1 Qiskit (IBM)",
                  children: [
                    {
                      content: "Circuit Construction",
                      children: [],
                      payload: { tag: "li", lines: "66,67" },
                    },
                    {
                      content: "Quantum Simulators",
                      children: [],
                      payload: { tag: "li", lines: "67,68" },
                    },
                    {
                      content: "Accessing Real Quantum Hardware",
                      children: [],
                      payload: { tag: "li", lines: "68,69" },
                    },
                    {
                      content: "Qiskit Textbook",
                      children: [],
                      payload: { tag: "li", lines: "69,71" },
                    },
                  ],
                  payload: { tag: "h3", lines: "65,66" },
                },
                {
                  content: "3.2 Cirq (Google)",
                  children: [
                    {
                      content: "Circuit Design",
                      children: [],
                      payload: { tag: "li", lines: "72,73" },
                    },
                    {
                      content: "Quantum Noise Simulation",
                      children: [],
                      payload: { tag: "li", lines: "73,74" },
                    },
                    {
                      content: "Integration with Google’s Quantum Processors",
                      children: [],
                      payload: { tag: "li", lines: "74,76" },
                    },
                  ],
                  payload: { tag: "h3", lines: "71,72" },
                },
                {
                  content: "3.3 PennyLane",
                  children: [
                    {
                      content: "Hybrid Quantum-Classical Computing",
                      children: [],
                      payload: { tag: "li", lines: "77,78" },
                    },
                    {
                      content: "Quantum Machine Learning",
                      children: [],
                      payload: { tag: "li", lines: "78,79" },
                    },
                    {
                      content: "PyTorch and TensorFlow Integration",
                      children: [],
                      payload: { tag: "li", lines: "79,81" },
                    },
                  ],
                  payload: { tag: "h3", lines: "76,77" },
                },
                {
                  content: "3.4 Q# (Microsoft)",
                  children: [
                    {
                      content: "Quantum Algorithm Design",
                      children: [],
                      payload: { tag: "li", lines: "82,83" },
                    },
                    {
                      content: "Quantum Development Kit (QDK)",
                      children: [],
                      payload: { tag: "li", lines: "83,84" },
                    },
                    {
                      content: "Integration with Azure Quantum",
                      children: [],
                      payload: { tag: "li", lines: "84,86" },
                    },
                  ],
                  payload: { tag: "h3", lines: "81,82" },
                },
              ],
              payload: { tag: "h2", lines: "64,65" },
            },
            {
              content: "4. Hands-On Practice",
              children: [
                {
                  content: "4.1 Tutorials",
                  children: [
                    {
                      content: "Qiskit Tutorials",
                      children: [],
                      payload: { tag: "li", lines: "88,89" },
                    },
                    {
                      content: "Cirq Demos",
                      children: [],
                      payload: { tag: "li", lines: "89,90" },
                    },
                    {
                      content: "PennyLane Use Cases",
                      children: [],
                      payload: { tag: "li", lines: "90,91" },
                    },
                    {
                      content: "Q# Documentation",
                      children: [],
                      payload: { tag: "li", lines: "91,93" },
                    },
                  ],
                  payload: { tag: "h3", lines: "87,88" },
                },
                {
                  content: "4.2 Projects",
                  children: [
                    {
                      content: "Simulate Quantum Gates",
                      children: [],
                      payload: { tag: "li", lines: "94,95" },
                    },
                    {
                      content: "Build Quantum Circuits",
                      children: [],
                      payload: { tag: "li", lines: "95,96" },
                    },
                    {
                      content: "Implement Quantum Algorithms",
                      children: [
                        {
                          content: "Grover's Search",
                          children: [],
                          payload: { tag: "li", lines: "97,98" },
                        },
                        {
                          content: "Deutsch-Josza Algorithm",
                          children: [],
                          payload: { tag: "li", lines: "98,99" },
                        },
                      ],
                      payload: { tag: "li", lines: "96,99" },
                    },
                    {
                      content: "Solve Quantum Challenges",
                      children: [
                        {
                          content: "Quantum Hackathons",
                          children: [],
                          payload: { tag: "li", lines: "100,101" },
                        },
                        {
                          content: "Online Coding Competitions",
                          children: [],
                          payload: { tag: "li", lines: "101,103" },
                        },
                      ],
                      payload: { tag: "li", lines: "99,103" },
                    },
                  ],
                  payload: { tag: "h3", lines: "93,94" },
                },
              ],
              payload: { tag: "h2", lines: "86,87" },
            },
            {
              content: "5. Advanced Topics",
              children: [
                {
                  content: "5.1 Quantum Cryptography",
                  children: [
                    {
                      content: "Quantum Key Distribution (QKD)",
                      children: [
                        {
                          content: "BB84 Protocol",
                          children: [],
                          payload: { tag: "li", lines: "106,107" },
                        },
                      ],
                      payload: { tag: "li", lines: "105,107" },
                    },
                    {
                      content: "Post-Quantum Cryptography",
                      children: [],
                      payload: { tag: "li", lines: "107,108" },
                    },
                    {
                      content: "Quantum Safe Algorithms",
                      children: [],
                      payload: { tag: "li", lines: "108,110" },
                    },
                  ],
                  payload: { tag: "h3", lines: "104,105" },
                },
                {
                  content: "5.2 Quantum Machine Learning",
                  children: [
                    {
                      content: "Quantum Neural Networks",
                      children: [],
                      payload: { tag: "li", lines: "111,112" },
                    },
                    {
                      content: "Variational Quantum Eigensolver (VQE)",
                      children: [],
                      payload: { tag: "li", lines: "112,113" },
                    },
                    {
                      content: "Quantum GANs",
                      children: [],
                      payload: { tag: "li", lines: "113,115" },
                    },
                  ],
                  payload: { tag: "h3", lines: "110,111" },
                },
                {
                  content: "5.3 Quantum Hardware",
                  children: [
                    {
                      content: "Types of Quantum Computers",
                      children: [
                        {
                          content: "Superconducting Qubits",
                          children: [],
                          payload: { tag: "li", lines: "117,118" },
                        },
                        {
                          content: "Trapped Ions",
                          children: [],
                          payload: { tag: "li", lines: "118,119" },
                        },
                        {
                          content: "Photonic Qubits",
                          children: [],
                          payload: { tag: "li", lines: "119,120" },
                        },
                      ],
                      payload: { tag: "li", lines: "116,120" },
                    },
                    {
                      content: "Quantum Hardware Access",
                      children: [
                        {
                          content: "IBM Quantum",
                          children: [],
                          payload: { tag: "li", lines: "121,122" },
                        },
                        {
                          content: "Rigetti",
                          children: [],
                          payload: { tag: "li", lines: "122,123" },
                        },
                        {
                          content: "D-Wave",
                          children: [],
                          payload: { tag: "li", lines: "123,125" },
                        },
                      ],
                      payload: { tag: "li", lines: "120,125" },
                    },
                  ],
                  payload: { tag: "h3", lines: "115,116" },
                },
              ],
              payload: { tag: "h2", lines: "103,104" },
            },
            {
              content: "6. Resources",
              children: [
                {
                  content: "6.1 Books",
                  children: [
                    {
                      content:
                        "<em>Quantum Computation and Quantum Information</em> by Nielsen and Chuang",
                      children: [],
                      payload: { tag: "li", lines: "127,128" },
                    },
                    {
                      content:
                        "<em>Quantum Computing for Everyone</em> by Chris Bernhardt",
                      children: [],
                      payload: { tag: "li", lines: "128,130" },
                    },
                  ],
                  payload: { tag: "h3", lines: "126,127" },
                },
                {
                  content: "6.2 Online Courses",
                  children: [
                    {
                      content: "IBM Quantum’s Free Tutorials",
                      children: [],
                      payload: { tag: "li", lines: "131,132" },
                    },
                    {
                      content: "edX Quantum Computing Program",
                      children: [],
                      payload: { tag: "li", lines: "132,133" },
                    },
                    {
                      content: "Qiskit Textbook",
                      children: [],
                      payload: { tag: "li", lines: "133,135" },
                    },
                  ],
                  payload: { tag: "h3", lines: "130,131" },
                },
                {
                  content: "6.3 Communities",
                  children: [
                    {
                      content: "IBM Quantum Community",
                      children: [],
                      payload: { tag: "li", lines: "136,137" },
                    },
                    {
                      content: "Quantum Open Source Foundation",
                      children: [],
                      payload: { tag: "li", lines: "137,138" },
                    },
                    {
                      content: "Reddit: r/QuantumComputing",
                      children: [],
                      payload: { tag: "li", lines: "138,140" },
                    },
                  ],
                  payload: { tag: "h3", lines: "135,136" },
                },
              ],
              payload: { tag: "h2", lines: "125,126" },
            },
            {
              content: "7. Career and Applications",
              children: [
                {
                  content: "7.1 Career Paths",
                  children: [
                    {
                      content: "Quantum Software Engineer",
                      children: [],
                      payload: { tag: "li", lines: "142,143" },
                    },
                    {
                      content: "Quantum Algorithm Developer",
                      children: [],
                      payload: { tag: "li", lines: "143,144" },
                    },
                    {
                      content: "Research Scientist",
                      children: [],
                      payload: { tag: "li", lines: "144,146" },
                    },
                  ],
                  payload: { tag: "h3", lines: "141,142" },
                },
                {
                  content: "7.2 Applications",
                  children: [
                    {
                      content: "Optimization Problems",
                      children: [],
                      payload: { tag: "li", lines: "147,148" },
                    },
                    {
                      content: "Drug Discovery",
                      children: [],
                      payload: { tag: "li", lines: "148,149" },
                    },
                    {
                      content: "Financial Modeling",
                      children: [],
                      payload: { tag: "li", lines: "149,150" },
                    },
                    {
                      content: "Machine Learning",
                      children: [],
                      payload: { tag: "li", lines: "150,151" },
                    },
                  ],
                  payload: { tag: "h3", lines: "146,147" },
                },
              ],
              payload: { tag: "h2", lines: "140,141" },
            },
          ],
          payload: { tag: "h1", lines: "0,1" },
        },
        null
      );
    </script>
  </body>
</html>

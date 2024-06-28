# Welcome to the Quantum Computing Learning Portal!

<style>
.circular-nav {
    position: relative;
    width: 600px; /* Increase width to accommodate the fourth button */
    height: 100px;
    background-color: white;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    border-radius: 25px; /* Rounded corners */
}

.nav-button {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    background-color: #0073e6;
    border: 2px solid #0073e6;
    font-size: 12px;
    color: #ffffff;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: transform 0.2s, box-shadow 0.2s;
}

.nav-button:hover {
    transform: scale(1.1);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

.nav-button i {
    margin-right: 8px; /* Space between icon and text */
}
</style>

<div class="circular-nav">
    <button class="nav-button" id="book"><i class="fas fa-book"></i> Book </button>
    <button class="nav-button" id="questions"><i class="fas fa-lightbulb"></i> Q&A</button>
    <button class="nav-button" id="cheatsheets"><i class="fas fa-text"></i> Cheat Sheets</button>
    <button class="nav-button" id="projects"><i class="fas fa-laptop"></i> Projects</button>
    <button class="nav-button" id="references"><i class="fas fa-text"></i> References </button>
</div>

<script>
document.getElementById('book').onclick = function() {
    window.location.href = 'https://learning.teachme.codes/quantum-computing/chapters/chapters';
};
document.getElementById('projects').onclick = function() {
    window.location.href = 'https://learning.teachme.codes/quantum-computing/projects/projects';
};
document.getElementById('questions').onclick = function() {
    window.location.href = 'https://learning.teachme.codes/quantum-computing/qnas/qnas';
};
document.getElementById('cheatsheets').onclick = function() {
    window.location.href = 'https://learning.teachme.codes/quantum-computing/cheats/cheats';
};
document.getElementById('references').onclick = function() {
    window.location.href = 'https://learning.teachme.codes/quantum-computing/refs/references';
};
</script>

| Book Chapters | Detail | References |
|--------|----------|-----|
| [Introduction to Quantum Computing](https://learning.teachme.codes/quantum_computing/chapters/introduction) | Quantum Computing is a field of computing focused on developing computer technology based on the principles of quantum theory, which explains the behavior of energy and material on the atomic and subatomic levels. | [IBM Quantum Computing](https://quantum-computing.ibm.com), [Microsoft Quantum](https://www.microsoft.com/en-us/quantum) |
| [Basic Quantum Mechanics](https://learning.teachme.codes/quantum_computing/chapters/basic_quantum_mechanics) | Basic Quantum Mechanics provides the fundamental principles that underlie quantum computing, including concepts like wave-particle duality, superposition, and entanglement. | [MIT OpenCourseWare](https://ocw.mit.edu/courses/physics/8-04-quantum-physics-i-spring-2013/index.htm), [Khan Academy](https://www.khanacademy.org/science/physics/quantum-physics) |
| [Quantum States and Qubits](https://learning.teachme.codes/quantum_computing/chapters/quantum_states_and_qubits) | Quantum States and Qubits are the basic units of quantum information. Qubits, unlike classical bits, can exist in multiple states simultaneously due to superposition. | [Qiskit Textbook](https://qiskit.org/textbook/ch-states/quantum-states.html), [Quantum Magazine](https://www.quantamagazine.org/what-is-a-qubit/) |
| [Quantum Superposition](https://learning.teachme.codes/quantum_computing/chapters/quantum_superposition) | Quantum Superposition refers to a quantum system's ability to be in multiple states at once until it is measured, a fundamental principle enabling the power of quantum computers. | [Quantum Magazine](https://www.quantamagazine.org/what-is-quantum-superposition-20201102/), [Scientific American](https://www.scientificamerican.com/article/quantum-superposition/) |
| [Quantum Entanglement](https://learning.teachme.codes/quantum_computing/chapters/quantum_entanglement) | Quantum Entanglement is a phenomenon where quantum states of two or more objects are interconnected such that the state of one object can instantly influence the state of another, regardless of distance. | [Nature](https://www.nature.com/subjects/quantum-entanglement), [Physics World](https://physicsworld.com/a/quantum-entanglement-what-is-it/) |
| [Quantum Gate Model](https://learning.teachme.codes/quantum_computing/chapters/quantum_gate_model) | Quantum Gate Model is the standard model for quantum computation, where computation is performed using a sequence of quantum gates, which are reversible transformations on qubits. | [IBM Quantum](https://quantum-computing.ibm.com/docs/circuit/gates), [Qiskit Textbook](https://qiskit.org/textbook/ch-gates/multiple-qubits-entangled-states.html) |
| [Quantum Circuit Model](https://learning.teachme.codes/quantum_computing/chapters/quantum_circuit_model) | Quantum Circuit Model represents quantum computations using quantum circuits, which consist of qubits and quantum gates. It is a widely used framework for designing and analyzing quantum algorithms. | [Qiskit Circuit Library](https://qiskit.org/documentation/apidoc/circuit_library.html), [Cambridge University](https://www.cambridge.org/core/what-we-publish/textbooks/quantum-computing-explained) |
| [Adiabatic Quantum Computing](https://learning.teachme.codes/quantum_computing/chapters/adiabatic_quantum_computing) | Adiabatic Quantum Computing relies on the adiabatic theorem, which ensures that a quantum system remains in its ground state as its Hamiltonian is slowly varied. It is used for solving optimization problems. | [D-Wave](https://www.dwavesys.com/tutorials/background-reading-series/adiabatic-quantum-computing), [Nature](https://www.nature.com/articles/nature24658) |
| [Topological Quantum Computing](https://learning.teachme.codes/quantum_computing/chapters/topological_quantum_computing) | Topological Quantum Computing uses anyons and topological states of matter to perform quantum computations. It is robust against local errors and is a promising approach for fault-tolerant quantum computing. | [Microsoft Quantum](https://www.microsoft.com/en-us/research/project/station-q/), [Nature](https://www.nature.com/articles/nature23460) |
| [Introduction to Quantum Algorithms](https://learning.teachme.codes/quantum_computing/chapters/quantum_algorithms) | Introduction to Quantum Algorithms covers the basics of algorithms designed for quantum computers, highlighting how they differ from classical algorithms in terms of complexity and performance. | [IBM Quantum Algorithms](https://quantum-computing.ibm.com/docs/algorithms), [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/algorithms-overview.html) |
| [Quantum Fourier Transform](https://learning.teachme.codes/quantum_computing/chapters/quantum_fourier_transform) | Quantum Fourier Transform is a linear transformation on quantum bits and is the quantum analogue of the discrete Fourier transform. It is a key component in many quantum algorithms. | [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/quantum-fourier-transform.html), [Cambridge University](https://www.cambridge.org/core/books/principles-of-quantum-computation-and-information/quantum-fourier-transform/7374D6E1E6174B9ACB23BF2EFC3A6B4A) |
| [Shor's Algorithm](https://learning.teachme.codes/quantum_computing/chapters/shors_algorithm) | Shor's Algorithm is a quantum algorithm for integer factorization, which efficiently solves a problem that is intractable for classical computers. It has significant implications for cryptography. | [IEEE](https://ieeexplore.ieee.org/document/9796147), [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/shor.html) |
| [Grover's Algorithm](https://learning.teachme.codes/quantum_computing/chapters/grovers_algorithm) | Grover's Algorithm is a quantum algorithm that provides a quadratic speedup for unstructured search problems. It is one of the most well-known quantum algorithms. | [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/grover.html), [Nature](https://www.nature.com/articles/s41586-019-0951-4) |
| [Quantum Phase Estimation](https://learning.teachme.codes/quantum_computing/chapters/quantum_phase_estimation) | Quantum Phase Estimation is a fundamental algorithm used to estimate the phase (or eigenvalue) of an eigenvector of a unitary operator. It is a key component in many quantum algorithms, including Shor's algorithm. | [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/quantum-phase-estimation.html), [Nature](https://www.nature.com/articles/s41567-019-0648-8) |
| [Quantum Simulation](https://learning.teachme.codes/quantum_computing/chapters/quantum_simulation) | Quantum Simulation uses quantum computers to simulate quantum systems, which is expected to provide insights into complex quantum phenomena and advance fields like materials science and chemistry. | [Quantum Computing Report](https://quantumcomputingreport.com/players/quantum-simulation/), [Nature](https://www.nature.com/articles/nature24658) |
| [Quantum Annealing](https://learning.teachme.codes/quantum_computing/chapters/quantum_annealing) | Quantum Annealing is a metaheuristic for solving optimization problems using quantum mechanics. It is used by quantum annealers like D-Wave to find the global minimum of a function. | [D-Wave](https://www.dwavesys.com/solutions-and-products/quantum-annealing/), [Springer](https://link.springer.com/article/10.1007/s11128-014-0769-7) |
| [Variational Quantum Eigensolver](https://learning.teachme.codes/quantum_computing/chapters/variational_quantum_eigensolver) | Variational Quantum Eigensolver (VQE) is a hybrid quantum-classical algorithm used to find the ground state energy of a quantum system. It is particularly useful in quantum chemistry and materials science. | [IBM Quantum](https://quantum-computing.ibm.com/docs/algorithms/variational-quantum-eigensolver), [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/variational-algorithms.html) |
| [Quantum Approximate Optimization Algorithm](https://learning.teachme.codes/quantum_computing/chapters/quantum_approximate_optimization_algorithm) | Quantum Approximate Optimization Algorithm (QAOA) is designed to solve combinatorial optimization problems. It uses a parameterized quantum circuit and classical optimization techniques to find approximate solutions. | [Nature](https://www.nature.com/articles/s41567-019-0648-8), [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/qaoa.html) |
| [Amplitude Amplification](https://learning.teachme.codes/quantum_computing/chapters/amplitude_amplification) | Amplitude Amplification is a generalization of Grover's algorithm that increases the probability amplitude of desired outcomes. It is used to boost the success probability of various quantum algorithms. | [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/amplitude-amplification.html), [Cambridge Quantum](https://cambridgequantum.com/amplitude-amplification/) |
| [Quantum Walks](https://learning.teachme.codes/quantum_computing/chapters/quantum_walks) | Quantum Walks are the quantum analog of classical random walks. They have applications in quantum search algorithms, graph algorithms, and other areas of quantum computation. | [Cambridge Quantum](https://cambridgequantum.com/quantum-walks/), [Qiskit Textbook](https://qiskit.org/textbook/ch-algorithms/quantum-walks.html) |
| [Quantum Machine Learning](https://learning.teachme.codes/quantum_computing/chapters/quantum_machine_learning) | Quantum Machine Learning combines quantum computing with machine learning algorithms to potentially achieve significant speedups and improvements in performance over classical methods. | [Springer](https://link.springer.com/book/10.1007/978-3-030-15723-4), [Nature](https://www.nature.com/articles/s41586-019-0951-4) |
| [Quantum Neural Networks](https://learning.teachme.codes/quantum_computing/chapters/quantum_neural_networks) | Quantum Neural Networks (QNN) are quantum versions of classical neural networks. They leverage quantum computing to enhance learning algorithms and are expected to provide exponential speedups in certain tasks. | [Nature](https://www.nature.com/articles/s41586-019-0951-4), [Springer](https://link.springer.com/article/10.1007/s00453-018-0383-3) |
| [Quantum Support Vector Machines](https://learning.teachme.codes/quantum_computing/chapters/quantum_support_vector_machines) | Quantum Support Vector Machines (QSVM) are the quantum counterparts of classical support vector machines. They use quantum computation to enhance classification tasks and can potentially solve problems more efficiently. | [Springer](https://link.springer.com/article/10.1007/s00453-018-0383-3), [IEEE](https://ieeexplore.ieee.org/document/8515642) |
| [Quantum Generative Adversarial Networks](https://learning.teachme.codes/quantum_computing/chapters/quantum_generative_adversarial_networks) | Quantum Generative Adversarial Networks (QGAN) are quantum versions of generative adversarial networks. They use quantum mechanics to improve the training and generation of data distributions. | [Nature](https://www.nature.com/articles/s41534-019-0029-7), [Springer](https://link.springer.com/article/10.1007/s00453-018-0383-3) |
| [Quantum Boltzmann Machines](https://learning.teachme.codes/quantum_computing/chapters/quantum_boltzmann_machines) | Quantum Boltzmann Machines are quantum versions of classical Boltzmann machines used for machine learning. They leverage quantum properties to potentially speed up the learning process and handle larger datasets. | [Springer](https://link.springer.com/article/10.1007/s10773-019-04148-2), [IEEE](https://ieeexplore.ieee.org/document/8515642) |
| [Quantum Clustering Algorithms](https://learning.teachme.codes/quantum_computing/chapters/quantum_clustering_algorithms) | Quantum Clustering Algorithms use quantum computation to perform clustering tasks in machine learning. They aim to provide more efficient and accurate clustering of large datasets. | [IEEE](https://ieeexplore.ieee.org/document/8515642), [Springer](https://link.springer.com/article/10.1007/s10773-019-04148-2) |
| [Quantum Principal Component Analysis](https://learning.teachme.codes/quantum_computing/chapters/quantum_principal_component_analysis) | Quantum Principal Component Analysis (QPCA) is a quantum algorithm that performs principal component analysis on quantum data. It is used to reduce the dimensionality of data and identify important features. | [Qiskit Textbook](https://qiskit.org/textbook/ch-applications/quantum-pca.html), [Nature](https://www.nature.com/articles/s41567-019-0648-8) |
| [Quantum Information Theory](https://learning.teachme.codes/quantum_computing/chapters/quantum_information_theory) | Quantum Information Theory studies the storage, transmission, and manipulation of information using quantum systems. It includes concepts like quantum entropy, quantum channels, and quantum error correction. | [Nature](https://www.nature.com/subjects/quantum-information), [Springer](https://link.springer.com/book/10.1007/978-3-030-57321-8) |
| [Quantum Cryptography](https://learning.teachme.codes/quantum_computing/chapters/quantum_cryptography) | Quantum Cryptography uses the principles of quantum mechanics to develop cryptographic protocols that are theoretically secure against any computational attack, such as quantum key distribution (QKD). | [Springer](https://link.springer.com/book/10.1007/978-3-030-57321-8), [IEEE](https://ieeexplore.ieee.org/document/9796147) |
| [Quantum Error Correction](https://learning.teachme.codes/quantum_computing/chapters/quantum_error_correction) | Quantum Error Correction involves methods to protect quantum information against errors due to decoherence and other quantum noise. It is essential for building reliable quantum computers. | [Qiskit Textbook](https://qiskit.org/textbook/ch-quantum-hardware/error-correction-repetition-code.html), [Nature](https://www.nature.com/articles/s41586-019-0951-4) |
| [Quantum Entropy](https://learning.teachme.codes/quantum_computing/chapters/quantum_entropy) | Quantum Entropy quantifies the uncertainty or randomness of a quantum state. It is a key concept in quantum information theory and has applications in quantum thermodynamics and quantum communications. | [Nature](https://www.nature.com/articles/nphys1170), [Springer](https://link.springer.com/book/10.1007/978-3-030-57321-8) |
| [Quantum Computing Applications](https://learning.teachme.codes/quantum_computing/chapters/quantum_computing_applications) | Quantum Computing Applications cover a range of fields where quantum computers are expected to have a significant impact, including cryptography, materials science, pharmaceuticals, and complex system simulations. | [IBM Quantum Applications](https://quantum-computing.ibm.com/applications), [Nature](https://www.nature.com/articles/nature24658) |
| [Quantum Communication](https://learning.teachme.codes/quantum_computing/chapters/quantum_communication) | Quantum Communication uses quantum mechanics to securely transmit information. It includes technologies like quantum key distribution (QKD) and quantum teleportation. | [Springer](https://link.springer.com/article/10.1007/s11128-014-0769-7), [Nature](https://www.nature.com/articles/s41586-019-1313-4) |
| [Quantum Sensing](https://learning.teachme.codes/quantum_computing/chapters/quantum_sensing) | Quantum Sensing uses quantum phenomena to measure physical quantities with high precision. Applications include atomic clocks, magnetometers, and gravitational wave detectors. | [Nature](https://www.nature.com/articles/s41586-019-1313-4), [IEEE](https://ieeexplore.ieee.org/document/8515642) |
| [Quantum Metrology](https://learning.teachme.codes/quantum_computing/chapters/quantum_metrology) | Quantum Metrology applies quantum theory to improve the accuracy of measurements. It leverages quantum entanglement and other phenomena to enhance the precision of sensors and measurement devices. | [Springer](https://link.springer.com/article/10.1007/s10773-020-04435-3), [Nature](https://www.nature.com/articles/nphys1170) |
| [Quantum Programming Languages](https://learning.teachme.codes/quantum_computing/chapters/quantum_programming_languages) | Quantum Programming Languages are designed for expressing quantum algorithms and controlling quantum computers. Examples include Qiskit, Cirq, and Quipper. | [Qiskit](https://qiskit.org/), [Google Cirq](https://quantumai.google/cirq) |
| [Quantum Software Frameworks](https://learning.teachme.codes/quantum_computing/chapters/quantum_software_frameworks) | Quantum Software Frameworks provide tools and libraries for developing and testing quantum algorithms. They include platforms like IBM Q Experience, Microsoft Q#, and Google's Cirq. | [IBM Q Experience](https://quantum-computing.ibm.com/), [Microsoft Q#](https://docs.microsoft.com/en-us/quantum/?view=qsharp-preview) |
| [Quantum Simulators](https://learning.teachme.codes/quantum_computing/chapters/quantum_simulators) | Quantum Simulators are classical systems designed to simulate quantum phenomena. They are used to test and develop quantum algorithms and to study quantum systems that are difficult to investigate experimentally. | [Quantum Computing Report](https://quantumcomputingreport.com/players/quantum-simulation/), [Nature](https://www.nature.com/articles/s41567-019-0648-8) |
| [Quantum Cloud Computing](https://learning.teachme.codes/quantum_computing/chapters/quantum_cloud_computing) | Quantum Cloud Computing provides access to quantum processors over the internet, allowing researchers and developers to run quantum algorithms on real quantum hardware remotely. | [IBM Cloud](https://www.ibm.com/cloud/quantum-computing), [Microsoft Azure](https://azure.microsoft.com/en-us/resources/development-kit/quantum-computing/) |
| [Quantum Development Kits](https://learning.teachme.codes/quantum_computing/chapters/quantum_development_kits) | Quantum Development Kits are collections of tools and resources for developing quantum software. They include quantum programming languages, simulators, and libraries for building and testing quantum applications. | [Microsoft Quantum Development Kit](https://azure.microsoft.com/en-us/resources/development-kit/quantum-computing/), [IBM Quantum](https://quantum-computing.ibm.com/docs/developers/tools)|


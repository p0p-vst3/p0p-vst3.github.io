<script lang="ts">
  import Waveform from "$lib/waveform.svg?raw";
</script>

<div id="page-container">
  <div id="title">
    <h1>p0p</h1><h2>-vst3</h2> 
  </div>
  <p>
    via <span id="rfhw">Retrofuturistic Hardware</span> @ <span id="gt">Georgia Tech</span>.
  </p>
  <div id="waveform-container">
    {@html Waveform}
  </div>
  <p>
    We build free and open-source audio software. <br />
    See our
    <a id="gh" href="https://github.com/p0p-vst3" 
       target="_blank" rel="noopener noreferrer">GitHub</a>.
  </p>
</div>

<style>
  #page-container {
    display: flex;
    flex-direction: column;
    gap: 0.4rem;
    transform: translateY(-2rem);
    padding: 0.25em;
  }
  #title {
    display: flex;
    align-items: flex-end;
  }
  h1 {
    font-weight: 900;
    font-size: 4rem;
  }
  h2 {
    font-weight: 600;
    font-size: 2rem;
    color: var(--gray);
  }
  p {
    font-size: 1em;
  }
  #waveform-container {
    width: 100%;
  }
  a {
    font-weight: 600;
    text-decoration: underline;
    transition: all 0.3s ease;
  }
  #rfhw {
    font-weight: 600;
    color: #4F7DE8;
  }
  #gt {
    font-weight: 600;
    color: #E3C978;
  }
  #gh {
    color: #E060CC;
  }
  #gh:hover {
    color: #fc9aed
  }
</style>

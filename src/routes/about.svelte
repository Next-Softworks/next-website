<script>
    import Header from "../components/header.svelte";
    import Interested from "../components/interested.svelte";
    import Footer from "../components/footer.svelte";
</script>

<Header/>

<div class="bg-white py-10 sm:py-20 lg:py-20">
    <div class="max-w-screen-md px-4 md:px-8 mx-auto">
      <h1 class="text-gray-800 text-3xl sm:text-4xl font-bold text-center mb-4 md:mb-6">Why Next ?</h1>
  
      <p class="text-gray-500 sm:text-lg mb-6 md:mb-8">
        This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of a real written text but is random or otherwise generated. It may be used to display a sample of fonts or generate text for testing. Filler text is dummy text which has no meaning however looks very similar to real text. The important factor when using filler text is that the text looks realistic otherwise it will not look very good.<br /><br />
  
        This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of a real written text but is <a href="#" class="text-indigo-500 hover:text-indigo-600 active:text-indigo-700 underline transition duration-100">random</a> or otherwise generated. It may be used to display a sample of fonts or generate text for testing. Filler text is dummy text which has no meaning however looks very similar to real text.
      </p>
  
      <h2 class="text-gray-800 text-xl sm:text-2xl font-semibold mb-2 md:mb-4">About us</h2>
  
      <p class="text-gray-500 sm:text-lg mb-6 md:mb-8">This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of a real written text but is random or otherwise generated. It may be used to display a sample of fonts or generate text for testing. Filler text is dummy text which has no meaning however looks very similar to real text.</p>
  
      <ul class="list-disc list-inside text-gray-500 sm:text-lg mb-6 md:mb-8">
        <li>This is a section of some simple filler text</li>
        <li>Also known as placeholder text</li>
        <li>It shares some characteristics of a real written text</li>
      </ul>
  
      <blockquote class="text-gray-500 sm:text-lg italic border-l-4 pl-4 md:pl-6 mb-6 md:mb-8">“This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of a real written text but is random or otherwise generated.”</blockquote>
  
      <div class="bg-gray-100 overflow-hidden rounded-lg shadow-lg relative mb-6 md:mb-8">
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src="https://images.unsplash.com/photo-1593508512255-86ab42a8e620?auto=format&q=75&fit=crop&w=600&h=350" loading="lazy" alt="Photo by Minh Pham" class="w-full h-full object-cover object-center" />
      </div>
  
      <h2 class="text-gray-800 text-xl sm:text-2xl font-semibold mb-2 md:mb-4">Features</h2>
  
      <p class="text-gray-500 sm:text-lg">This is a section of some simple filler text, also known as placeholder text. It shares some characteristics of a real written text but is random or otherwise generated. It may be used to display a sample of fonts or generate text for testing. Filler text is dummy text which has no meaning however looks very similar to real text.</p>
    </div>
  </div>

  <div class="py-32 px-4 mx-auto max-w-screen-xl lg:py-19 lg:px-6">
    <div class="mx-auto max-w-screen-sm text-center">
        <p class="mb-4 text-3xl tracking-tight font-bold text-gray-900 md:text-4xl">Ready to made your brand?</p>
        <p class="mb-4 text-lg font-light text-gray-500">Sorry, we can't find that page. You'll find lots to explore on the home page. </p>
        <a href="/contact" class="inline-flex text-white bg-indigo-500 hover:bg-indigo-600 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-xl text-sm px-5 py-2.5 text-center">Get Quote</a>
    </div>   
</div>
<Footer/>
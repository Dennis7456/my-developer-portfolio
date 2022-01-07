<script>
    import FacebookIcon from './facebook-icon.svelte'
    import TwitterIcon from './twitter-icon.svelte'
    import YoutubeIcon from './you-tube-icon.svelte'
</script>

<footer class="p-10 footer bg-primary text-primary-content footer-center">
    <div class="grid grid-flow-col gap-4">
      <a class="link link-hover" href="/projects">Portfolio</a> 
      <a class="link link-hover" href="/posts">Blog</a> 
      <a class="link link-hover" href="/about">About</a> 
    </div> 
    <div>
      <div class="grid grid-flow-col gap-4">
        <a href="https://twitter.com/DennisTheDev1">
          <TwitterIcon />
        </a> 
        <a href="https://www.youtube.com/channel/UCIl1IjCrO9BENNtrZetkcyg">
            <YoutubeIcon />
        </a> 
        <a href="https://www.facebook.com/dennis.kiplangat.1297">
            <FacebookIcon />
        </a>
      </div>
    </div> 
    <div>
      <p>
          Copyright &copy; { `${new Date().getFullYear()}`} - All rights reserved by me.
        </p>
    </div>
  </footer>
<script lang="ts">
	import LinkInfo from '$lib/components/LinkInfo/LinkInfo.svelte';
	import mirrorUniverse from '$lib/images/mirror_universe.png';

	async function skipped() {
		var $pod = jQuery('#pod');
		var $skipMessage = jQuery('#skipMessage');
		$pod[0].scrollIntoView({ behavior: 'smooth', block: 'center', inline: 'nearest' });
		$pod.addClass('bg-yellow-600');
		$skipMessage.removeClass('opacity-0').addClass('bg-yellow-600');
		setTimeout(() => {
			$pod.removeClass('bg-yellow-600');
			$skipMessage.removeClass('bg-yellow-600');
		}, 2000);
	}
</script>

<h3>BEYOND SIMULATION HYPOTHESIS</h3>

<p>
	Please bear with me while I do a little bit of fictional storytelling. I am going somewhere with
	all this, I promise, but if you're impatient, you can <a
		href="#blank"
		on:click|preventDefault={skipped}
		class="indent-0"
	>
		skip to the part where you're already 🤬ed off
	</a>.
</p>
<p>
	We are going to start with a concept with which most of us are familiar – specifically, a video
	game. Allow us to imagine that I am going to create a new one. Personally, I'm fairly terrible at
	thinking of new ideas, so I’m just going to steal some – mainly from <LinkInfo
		title="Wikipedia > Maxis"
		href="https://en.wikipedia.org/wiki/Maxis#:~:text=Maxis%20is%20an%20American%20video%20game%20developer%20and%20a%20division%20of%20Electronic%20Arts%20(EA).%20The%20studio%20was%20founded%20in%201987%20by%20Will%20Wright%20and%20Jeff%20Braun%2C%20and%20acquired%20by%20EA%20in%201997.%20Maxis%20is%20best%20known%20for%20its%20simulation%20games%2C%20including%20The%20Sims%2C%20Spore%20and%20SimCity."
		hoverExcerpt="An American video game developer bset known for its simulation games, including <em>The Sims</em>, <em>Spore</em>, and <em>SimCity</em>."
		excerpt="Maxis is an American video game developer and a division of Electronic Arts (EA). The studio was founded in 1987 by Will Wright and Jeff Braun, and acquired by EA in 1997. Maxis is best known for its simulation games, including <em>The Sims</em>, <em>Spore</em> and <em>SimCity</em>."
		>Maxis</LinkInfo
	>. I'm going to blend elements of <LinkInfo
		title="Wikipedia > SimEarth"
		href="https://en.wikipedia.org/wiki/SimEarth#:~:text=SimEarth%20is%20a%20life%20simulation%20video%20game%2C%20the%20second%20designed%20by%20Will%20Wright%20and%20published%20in%201990%20by%20Maxis.%20In%20SimEarth%2C%20the%20player%20controls%20the%20development%20of%20a%20planet.%20English%20scientist%20James%20Lovelock%20served%20as%20an%20advisor%20and%20his%20Gaia%20hypothesis%20of%20planet%20evolution%20was%20incorporated%20into%20the%20game."
		hoverExcerpt="A life simulation video game, where the player controls the development of a planet."
		excerpt="SimEarth is a life simulation video game, the second designed by Will Wright and published in 1990 by Maxis. In SimEarth, the player controls the development of a planet. English scientist James Lovelock served as an advisor and his Gaia hypothesis of planet evolution was incorporated into the game."
		>SimEarth</LinkInfo
	>
	(1990) with aspects of <LinkInfo
		title="Wikipedia > Spore"
		href="https://en.wikipedia.org/wiki/Spore_(2008_video_game)#:~:text=Spore%20is%20a,a%20spacefaring%20culture."
		hoverExcerpt="A life simulation game that allows a player to control the development of a species from its beginnings as a microscopic organism through development as an intelligent and social creature."
		excerpt="Spore is a 2008 life simulation real-time strategy God game developed by Maxis and published by Electronic Arts for Microsoft Windows and Mac OS X. Designed by Will Wright, it covers many genres including action, real-time strategy, and role-playing games. Spore allows a player to control the development of a species from its beginnings as a microscopic organism, through development as an intelligent and social creature, to interstellar exploration as a spacefaring culture."
		>Spore</LinkInfo
	>
	(2008), into a modern, ultra-realistic simulation called
	<span style="text-decoration:underline;">SporeEarth</span>. In the game, you can utilize and
	modify an entire planet’s resources to create the most successful and intelligent species
	possible. And I'll “borrow” the idea from
	<span style="text-decoration:underline;">SimEarth's</span>
	<LinkInfo
		title="Wikipedia > SimEarth"
		href="https://en.wikipedia.org/wiki/SimEarth#:~:text=In%20the%20%E2%80%9CRandom%20Planet%E2%80%9D%20game%20setting%2C%20the%20game%20is%20a%20software%20toy%2C%20without%20any%20required%20goals."
		hoverExcerpt="Setting that makes the game a software toy you can watch instead of play."
		excerpt="In the “Random Planet” game setting, the game is a software toy, without any required goals."
		><em>Random Planet</em></LinkInfo
	>
	setting, which means you can opt to invoke the laws of chaos and then just sit back and watch what
	happens, rather than actually interacting with the game. Fittingly,
	<span style="text-decoration:underline;">SporeEarth</span>
	would fit squarely in a genre of gaming called
	<LinkInfo
		title="Wikipedia > God game"
		href="https://en.wikipedia.org/wiki/God_game#:~:text=A%20god%20game,guard%20and%20influence."
		hoverExcerpt="A game that casts the player in the position of controlling the game as an entity with divine and supernatural powers."
		excerpt="A god game is an artificial life game that casts the player in the position of controlling the game on a large scale, as an entity with divine and supernatural powers, as a great leader, or with no specified character (as in Spore), and places them in charge of a game setting containing autonomous characters to guard and influence."
		>god games</LinkInfo
	>.
</p>
<p>
	Since this is my story, and I’m telling it, I’m going to seriously bend reality here: I totally
	nailed it. Envision that I made a super-addictive video game that spanned the globe on multiple
	gaming platforms, raking in a couple billion in sales. Sweet!
</p>
<p>
	A few years roll by, and by that time I will have blown through <em>all</em> the money I made from
	that game, mostly via defending myself against various pesky copyright lawsuits. After settling
	out of court in such a manner that I retain rights to the work, I’ll borrow again – this time,
	capital instead of only ideas. I’ll secure loans, hire Sierra Hotel developers and start my next
	game. But this time, instead of simulating one boring planet, I’m going to scale this sucker up
	and do an entire universe! For obvious reasons, and because outside certain compartments I am
	pathetically unoriginal, I am going to call this game
	<span style="text-decoration:underline;">SporeUniverse</span>. Now a player can wield the
	resources of all known creation, starting from the
	<LinkInfo
		title="Wikipedia > Big Bang"
		href="https://en.wikipedia.org/wiki/Big_Bang#:~:text=The%20Big%20Bang%20event,subsequent%20large%2Dscale%20form."
		hoverExcerpt="Theory that describes how the universe expanded from an initial state of high density and temperature."
		excerpt="The Big Bang event is a physical theory that describes how the universe expanded from an initial state of high density and temperature. Various cosmological models of the Big Bang explain the evolution of the observable universe from the earliest known periods through its subsequent large-scale form."
		>big bang</LinkInfo
	>, multiplying the chances of creating successful life-forms and civilizations. You must shape
	galaxies and planets, then kick off just the optimal number of supernova explosions that will seed
	galaxies with the heavy elements required for complex life. Once life has begun, you must guide
	that life through evolution. And yep - just like with
	<span style="text-decoration:underline;">SporeEarth</span>, you can sit back and watch the fun
	with the <em>Random Universe<strong /></em> setting, if you so desire.
</p>
<p>
	Again, success! We collectively garner another couple billion in sales. This time, I get to keep
	some of the money, and I become moderately wealthy after paying off what I borrowed (as well as
	paying all my developers and subcontractors handsomely and fairly for their amazing work).
</p>
<p>
	Some years later, I'll have decided I want to take aim at retirement, so the team gets called back
	up for one last new version. Everyone has their own preferences and ideas but, personally, I tire
	of single-player games rather quickly after I’ve played them through a few times. Much more
	importantly, it’s now time for some recurring revenue with a subscription-based model. So, I
	direct my team to make <span style="text-decoration:underline;">SporeUniverse 2,</span> an online two-player
	game. You now have an opponent, and your goal is to defeat them by having better or more successful
	civilizations. You will still launch with the same finite resources of one universe. So, of course,
	you must compete with your opponent over those resources (and then manage them properly) in order to
	win.
</p>
<div class="indent-8">
	Now, to make this game way more interesting: you can also use your moves <em>destructively</em> to
	sabotage your opponent. Possible wrench-in-gear scenarios include:
	<ul class="list-disc p-4 pl-8 indent-0">
		<li>
			Inciting end-times hickeys such as war, genocide, or nuclear holocaust among your opponent’s
			sentient populations.
		</li>
		<li>
			Attempting modifications to the course of asteroids without your opponent noticing, triggering
			mass (or worldwide) extinction when the opposition’s planets are hit.
		</li>
		<li>
			Aiming a <LinkInfo
				title="Wikipedia > Gamma-ray burst"
				href="https://en.wikipedia.org/wiki/Gamma-ray_burst#:~:text=In%20gamma%2Dray,neutron%20stars."
				hoverExcerpt="Energetic explosions of stars that are the largest and most luminous events since the big bang."
				excerpt="In gamma-ray astronomy, gamma-ray bursts (GRBs) are immensely energetic explosions that have been observed in distant galaxies. They are the most energetic and luminous electromagnetic events since the Big Bang. Bursts can last from ten milliseconds to several hours. After an initial flash of gamma rays, a longer-lived “afterglow” is usually emitted at longer wavelengths (X-ray, ultraviolet, optical, infrared, microwave and radio).<br /><br />
			The intense radiation of most observed GRBs is thought to be released during a supernova or superluminous supernova as a high-mass star implodes to form a neutron star or a black hole. A subclass of GRBs appear to originate from the merger of binary neutron stars."
				>gamma ray burst</LinkInfo
			> at just the right spot so it squeegees a planet clean of life.
		</li>
		<li>
			Or the ultimate in destructive power; using your moves to accelerate supernovae (or
			hypernovae) explosions that destroy regions of galaxies hundreds of light-years across at
			99.999% the speed of light!
		</li>
	</ul>
</div>
<p class="pb-2">
	Given these amazing additions, all in-game purchases naturally, our company once again rakes in
	lots of dough, making my development team multi-millionaires. I crack the .1%, and it’s now time
	for me to hang it up and become a world-traveling philanthropist.
</p>
<div class="pt-2 pb-2 indent-8 transition-colors duration-[2000ms] rounded-md" id="pod">
	<strong>
		What does this have to do with reality? How is this scientific at all? All you’ve done is talk
		about video games and created a delusional scenario for yourself in which you make a bunch of
		money.”
	</strong>
</div>
<p class="pt-2">
	Ouch. Well-played, you.<span
		id="skipMessage"
		class="pl-1 pr-1 opacity-0 transition-all duration-[2000ms]"
		>(Now, would you please go back and at least <em>skim</em> the part you skipped?)</span
	>
</p>
<p>
	Stepping back to (single-player) <span style="text-decoration:underline;">SporeUniverse’s</span>
	<em>Random Universe</em>
	setting, this is basically what the<LinkInfo
		title="Wikipedia > Simulation hypothesis"
		href="https://en.wikipedia.org/wiki/Simulation_hypothesis#:~:text=The%20simulation%20hypothesis%20proposes,of%20philosophical%20skepticism."
		hoverExcerpt="Hypothesis that proposes that all of our existence is a simulated reality."
		excerpt="The simulation hypothesis proposes that all of our existence is a simulated reality, such as a computer simulation.<br /><br />
			The simulation hypothesis bears a close resemblance to various other skeptical scenarios from throughout the history of philosophy. The hypothesis was popularized in its current form by Nick Bostrom. The suggestion that such a hypothesis is compatible with all human perceptual experiences is thought to have significant epistemological consequences in the form of philosophical skepticism."
		>simulation hypothesis</LinkInfo
	> suggests. That we, and our entire universe, are all part of a very advanced civilization’s simulation.
	Given that they have been around for billions (or even trillions) of years, they are
	<em>very</em> bored; ennui enough and more to wait around and watch what happens when they invest vast
	amounts of energy and computing power to create random universes on virtual machines to see what might
	happen. Regardless, if the hypothesis is correct, one of those beings could be God from our perspective,
	since they literally created (or at least control) all we know to exist.
</p>
<p>
	The same would be true for <span style="text-decoration:underline;">SporeUniverse 2</span>, where
	to us, <em>both</em> players would be gods. Now, imagine what happens if we were to strip away the
	game construct, and imbue the two players with opposing anthropomorphic characteristics: pure love
	and pure evil. From this standpoint, we can start to see how it would look like a religion from the
	perspective of the beings inside that universe. One god is good, doing his best to create and grow
	life and civilizations. By contrast, the other god is an evil jerk, who creates nothing and spends
	his time doing his best to kick over metaphorical sandcastles out of hatred and spite.
</p>
<p>
	Re-implementing the game concept, I would now like to make a final modification. At the start of
	the game, you are granted your own observable universe (or OU). The big bang begins (click
	"Start"!) and hurls an inconceivable amount of matter and energy (and therefore spacetime) into
	existence for your use and disposal. But it’s symmetrical – your opponent also receives their own
	OU and the same exact amount of matter and energy. Note that in this context, “observable”<em
	/>does not mean from one frame of reference, such as Earth’s. Rather, observable means you could
	move freely through <em>every</em> frame of reference throughout that entire universe, from a God’s-eye-view.
</p>
<p>
	<strong
		>“All right, but if you are both playing in your own sandboxed OUs, how are you supposed to
		sabotage your enemy now? Isn’t this the same as both players stepping back to the first <span
			style="text-decoration:underline;">SporeUniverse</span
		> and comparing which universe is better to see who wins?”</strong
	>
</p>
<p>
	The “secret sauce” here is that both the OUs <em>can</em> interact. The matter and energy granted
	to both players are quite literally two sides of the same coin. The big bang creates a
	universe/anti-universe <em>pair</em>. The matter granted to each player’s universe becomes their
	opponent’s anti-matter, and all of it is bound together through quantum fields, interactions, and
	<LinkInfo
		title="Wikipedia > Quantum entanglement"
		href="https://en.wikipedia.org/wiki/Quantum_entanglement#:~:text=Quantum%20entanglement%20is,in%20classical%20mechanics."
		hoverExcerpt="Phenomenon wherein multiple particles interact in a way such that the quantum state of a particle cannot be described independently of other particles."
		excerpt="Quantum entanglement is the phenomenon that occurs when a group of particles are generated, interact, or share spatial proximity in a way such that the quantum state of each particle of the group cannot be described independently of the state of the others, including when the particles are separated by a large distance. The topic of quantum entanglement is at the heart of the disparity between classical and quantum physics: entanglement is a primary feature of quantum mechanics not present in classical mechanics."
		>entanglement</LinkInfo
	>. Both universes progress forward ("time’s arrow") from the big bang, but they progress in
	opposite time directions relative to each other. Both OUs have their own 4-dimensional spacetime,
	but they are sitting directly on top of one another, occupying the same physical space (analogous
	to a hologram), separated only temporally. Because of the time differential, matter in each OU
	cannot directly interact with matter in the other. The players, however, may, and do, observe both
	OUs.
</p>
<p>
	Now, the only way the players make any moves at all is through quantum interactions. In fact, to
	the beings (and matter) inside both OUs, the quantum world becomes the base level of reality
	itself. Quantum fields and particles, existing in superpositions of possible states, permeate each
	OU. A move occurs when particles in your OU interact with other particles, thus initiating <LinkInfo
		title="Wikipedia > Wave function collapse"
		href="https://en.wikipedia.org/wiki/Wave_function_collapse#:~:text=In%20quantum%20mechanics,Schr%C3%B6dinger%20equation."
		hoverExcerpt="When a wave function in a superposition of eigenstates reduces to a single eigenstate due to interaction with the external world."
		excerpt="In quantum mechanics, wave function collapse occurs when a wave function—initially in a superposition of several eigenstates—reduces to a single eigenstate due to interaction with the external world. This interaction is called an observation, and is the essence of a measurement in quantum mechanics, which connects the wave function with classical observables such as position and momentum. Collapse is one of the two processes by which quantum systems evolve in time; the other is the continuous evolution governed by the Schrödinger equation."
		>wave function collapse</LinkInfo
	>. At that instant, a query occurs, and a “path”, or an
	<LinkInfo
		title="Wikipedia > Intoduction to eigenstates"
		href="https://en.wikipedia.org/wiki/Introduction_to_eigenstates#:~:text=The%20word%20%22eigenstate,called%20an%20eigenvalue."
		hoverExcerpt="The measured state of an object possessing quantifiable characteristics, such as position, momentum, etc."
		excerpt="The word “eigenstate” is derived from the German/Dutch word “eigen”, meaning “inherent” or “characteristic”. An eigenstate is the measured state of some object possessing quantifiable characteristics such as position, momentum, etc. The state being measured and described must be observable (i.e. something such as position or momentum that can be experimentally measured either directly or indirectly), and must have a definite value, called an eigenvalue."
		>eigenstate</LinkInfo
	>, must be chosen. Particles might be entangled with others within the same OU, which means your
	move might affect only your OU. But in instances when particles are entangled across both OUs, a
	percentage of your move affects your OU, while another percentage affects your opponent’s.
</p>
<p>
	Your goal is now to use these quantum interactions to slowly and deliberately shape your OU. When
	you get the opportunity to use cross-OU-entangled moves, the objective is to simultaneously
	benefit your OU while stifling your opponent’s progress through entropy, chaos and destruction.
	When selecting eigenstates, you are working either with or against the probability available in
	each wave function. You have a finite amount of “energy” in terms of the improbability you can
	work against in a single move, meaning the amount of energy your move consumes is proportional to
	how improbable your selections are.
</p>
<p>
	Obviously, it would be completely impractical for this game to be played by humans. We would have
	to make more decisions in a single second than we have <em>nanoseconds</em> in our entire
	lifetimes, perhaps by hundreds of orders of magnitude. This would be a game for highly advanced
	consciousnesses with incredibly vast amounts of processing power. For simplicity’s sake, I will
	refer to them each as a godlike-consciousness (or GC). And, yes, this is exactly what I am
	suggesting – that something similar to this construct could be the very foundation of our universe
	and our existence. Two GCs, or players, or gods, or whatever-you<em>-</em>choose-to-call-them, are
	competing to create the more-conscious universe.
</p>
<p>
	We can call the OU we exist within the <em>proverse</em>, and we can call the OU that exists
	outside ours the <em>antiverse</em>. Following suit, we can call the godlike-consciousness
	controlling our universe the <em>proverse GC</em> (or PGC), while the GC controlling the
	anti-universe becomes the <em>antiverse GC</em> (or AGC).
</p>
<div class="pb-6">
	<img class="mx-auto" alt="Mirror Universes" src={mirrorUniverse} />
	<div class="text-sm text-center">The Proverse/Antiverse Pair</div>
</div>
<p>
	<strong
		>“Wait, seriously? You’re trying to convince me that the entire universe is just part of some
		game?”</strong
	>
</p>
<div class="indent-8">
	Well, sort of. A competition of some sort is likely in play. Based on the nature of physics, a
	game appears to be the most logical scenario. There are many possible reasons for the competition,
	including:
	<ul class="list-disc p-4 pl-8 indent-0">
		<li>
			It could be compared to friendly game of digital chess – a way to pass the trillions and
			trillions of years of deep time available to such beings.
		</li>
		<li>
			It could be a game with a wager-style system, where each GC stands to gain something if they
			win (more energy or resources, perhaps?)
		</li>
		<li>
			It could be a game with incredibly high stakes; i.e., whoever ultimately loses is destroyed or
			is compelled to self-annihilate.
		</li>
		<li>
			Or... perhaps it is not a game at all. If you envision this reality without the game
			construct, the two GCs could somehow be actively engaging in real, physical combat, where one
			victor ultimately defeats or even kills the other.
		</li>
	</ul>
</div>
<p>
	Any of these reasons are a possibility, but unless there was a way for us to discover which, it is
	irrelevant from our standpoint. And I know what you are thinking – that this can’t possibly
	describe our actual reality. But I implore you to read on to understand how this is fundamentally
	conceivable.
</p>
<p>
	<strong>“Why is this a two-player game? Why not 4, 8, or an MMO?”</strong>
</p>
<p>
	There could be more players. But there are several reasons I choose two players for now, including
	that from what we currently know, matter and antimatter (and CPT symmetry – more on this later)
	seem to be a duality, not a multiplicity. That said, there could be billions of GCs working
	cooperatively in each OU. Again, though – from our standpoint, it does not really matter if there
	are two masses of collective consciousnesses, or if there are singular GCs per OU. To us, the end
	result is effectively the same.
</p>
<p>
	<strong>“So, you’re implying there’s a parallel universe?”</strong>
</p>
<p>
	That is correct. BDI predicts that a symmetric universe exists alongside ours, one that we cannot
	visit or easily detect. However, it is important to distinguish this from the science fiction
	version of a <LinkInfo
		title="Wikipedia > Parallel universes in fiction"
		href="https://en.wikipedia.org/wiki/Parallel_universes_in_fiction#:~:text=A%20parallel%20universe,alternate%20history."
		hoverExcerpt="A hypothetical self-contained plane of existence, with generally implied overlap with our own reality."
		excerpt="A parallel universe, also known as a parallel dimension, alternate universe, or alternate reality, is a hypothetical self-contained plane of existence, co-existing with one's own. The sum of all potential parallel universes that constitute reality is often called a “multiverse”.<br /><br />
		While the four terms are generally synonymous and can be used interchangeably in most cases, there is sometimes an additional connotation implied with the term “alternate universe/reality” that implies that the reality is a variant of our own, with some overlap with the similarly named alternate history."
		>parallel universe</LinkInfo
	>, where if you were transported there from where you are now, you would be standing on a
	different version of Earth. The antiverse would have the same physics as our universe, and would
	have started out with the same amount of matter. As such, it would certainly have planets that
	could (or would) sustain life, but due to the vast number of quantum interactions that occurred
	directly subsequent to the big bang, it is vanishingly unlikely that <em>any</em> version of our Earth
	would exist. And, due to the vast emptiness of space, if you were theoretically teleported to the same
	relative place you occupy in our OU to theirs, you would almost certainly end up floating (and dying)
	in deep space – even ignoring the fact that your body would be made of antimatter there, and all the
	nastiness that could involve.
</p>
<p>Next, using this framework, let’s make some predictions.</p>

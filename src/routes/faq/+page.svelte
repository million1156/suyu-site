<script lang="ts">
	import tuta from "$assets/branding/tuta.png";
</script>

<svelte:head>
	<title>FAQ</title>
</svelte:head>

<div
	class="relative flex w-full flex-col gap-6 overflow-hidden rounded-[2.25rem] bg-[#110d10] p-8 md:p-12"
>
	<svg
		xmlns="http://www.w3.org/2000/svg"
		width="512"
		height="525"
		viewBox="0 0 512 525"
		fill="none"
		style="animation-duration: 300s; transform-origin: 50% 50%; animation-iteration-count: infinite; animation-timing-function: linear; animation-name: spin; animation-delay: 0s; animation-direction: normal; animation-fill-mode: none; animation-play-state: running;"
		class="pointer-events-none absolute -bottom-[18rem] right-0 z-0 animate-spin opacity-20"
	>
		<path
			d="M511.5 262.12C511.5 353.613 465.547 434.182 396.019 480.947C408.179 457.937 415.083 431.597 415.083 403.617C415.083 313.723 343.816 240.744 255.992 240.744C191.257 240.744 138.692 186.941 138.692 120.622C138.692 54.3027 191.257 0.5 255.992 0.5C397.026 0.5 511.5 117.695 511.5 262.12ZM255.992 53.5225C243.745 53.5225 233.816 63.7047 233.816 76.2224C233.816 88.7388 243.745 98.9223 255.992 98.9223C268.257 98.9223 278.173 88.7387 278.173 76.2224C278.173 63.7048 268.257 53.5225 255.992 53.5225ZM299.355 97.9223C287.104 97.9223 277.173 108.104 277.173 120.622C277.173 133.139 287.104 143.322 299.355 143.322C311.62 143.322 321.536 133.139 321.536 120.622C321.536 108.104 311.62 97.9223 299.355 97.9223ZM212.635 97.9223C200.382 97.9223 190.455 108.104 190.455 120.622C190.455 133.139 200.382 143.322 212.635 143.322C224.889 143.322 234.816 133.139 234.816 120.622C234.816 108.104 224.888 97.9223 212.635 97.9223ZM255.992 142.322C243.745 142.322 233.816 152.505 233.816 165.021C233.816 177.539 243.745 187.721 255.992 187.721C268.257 187.721 278.173 177.538 278.173 165.021C278.173 152.505 268.257 142.322 255.992 142.322Z"
			stroke="white"
		/>
		<path
			d="M0.5 262.119C0.5 170.626 46.444 90.0553 115.976 43.2909C103.82 66.3019 96.9172 92.6424 96.9172 120.622C96.9172 210.516 168.174 283.495 255.992 283.495C320.735 283.495 373.305 337.298 373.305 403.617C373.305 469.934 320.735 523.739 255.992 523.739C114.974 523.739 0.5 406.544 0.5 262.119ZM255.992 336.517C243.744 336.517 233.816 346.7 233.816 359.217C233.816 371.735 243.745 381.917 255.992 381.917C268.256 381.917 278.173 371.735 278.173 359.217C278.173 346.701 268.256 336.517 255.992 336.517ZM299.355 380.917C287.104 380.917 277.173 391.099 277.173 403.617C277.173 416.135 287.104 426.317 299.355 426.317C311.619 426.317 321.536 416.135 321.536 403.617C321.536 391.099 311.619 380.917 299.355 380.917ZM255.992 425.317C243.745 425.317 233.816 435.499 233.816 448.016C233.816 460.533 243.744 470.717 255.992 470.717C268.256 470.717 278.173 460.533 278.173 448.016C278.173 435.499 268.256 425.317 255.992 425.317ZM212.634 380.917C200.382 380.917 190.454 391.099 190.454 403.617C190.454 416.135 200.382 426.317 212.634 426.317C224.888 426.317 234.816 416.135 234.816 403.617C234.816 391.099 224.888 380.917 212.634 380.917Z"
			stroke="white"
		/>
	</svg>

	<h1 class="text-[24px] leading-[1.41] md:text-[60px] md:leading-[1.1]">
		FAQ
	</h1>
	<p class="max-w-[36rem] text-lg leading-relaxed text-[#A6A5A7]">
		Got some questions? We got answers!
	</p>
    <p class="text-[15px] leading-[1.41] md:text-[19px] md:leading-[1.1]">Q: How is this project different from Yuzu? How do we know you won't have the same fate as Yuzu?</p>
	<p class= "text-m text-[15px]">A: Unlike Yuzu, Suyu does <b>not</b> include many of the core "requirements" to run it. You need to legally dump your Nintendo Switch to obtain a title.keys file, which Yuzu did not do. Additionally, you must dump your own firmware.</p>
	<p class="text-[15px] leading-[1.41] md:text-[19px] md:leading-[1.1]">Q: What is the purpose of Suyu?</p>
	<p class= "text-m text-[15px]">A: The purpose of this project is to provide a free, open-source alternative to the now-dead Yuzu emulator. We believe that the community should be able to emulate their Switch device (legally) and be able to enjoy their favorite game titles.</p>
	<p class="text-[15px] leading-[1.41] md:text-[19px] md:leading-[1.1]">Q: How can I contribute to Suyu?</p>
	<p class= "text-m text-[15px]">A: You can contribute to this project by submitting a pull request on our <a href="https://git.suyu.dev/suyu/suyu"><u>Git</u></a> page. We are always looking for new contributors to help us improve the project!</p>
	<p class="text-[15px] leading-[1.41] md:text-[19px] md:leading-[1.1]">Q: Where can I download Suyu?</p>
	<p class= "text-m text-[15px]">A: You can download the latest build of Suyu from our <a href="https://git.suyu.dev/suyu/suyu/releases"><u>Git</u></a>. Please make sure you are using the right URL!</p>
	<p class="text-[15px] leading-[1.41] md:text-[19px] md:leading-[1.1]">Q: What is the current progress for Suyu?</p>
	<p class= "text-m text-[15px]">A: As of 3/20/2024, we have released our first Windows binary 🎉! You can find it <a href="https://git.suyu.dev/suyu/suyu/releases"><u>here</u></a>. We are always trying to make more and more progress, so please feel free to <a href="https://discord.gg/suyu"><u>join the Discord!</u></a></p>
	<br />
	<div class="leading-[1.41] items-center text-[15px] md:leading-[1.1] flex gap-2 text-gray-600">Email hosting lovingly provided by
		<a href="https://tuta.com" target="_blank">
			<img src={tuta} alt="Tuta" width={102} height={24} class="h-[24px] rounded-md" />
		</a>
	</div>
</div>

<script lang="ts">
	import {
		Presentation,
		Slide,
		Vertical,
		Layout,
		Step,
		Code,
	} from '@components'

	import VSCodeIcon from './assets/vscode.png'
	import HTMLIcon from './assets/html.png'
	import DiscordIcon from './assets/discord.png'
	import GithubIcon from './assets/github.webp'

	import PreviewIndex from './assets/result/index.png'
	import PreviewDetail from './assets/result/detail.png'

	import VSCodeInstall0 from './assets/instalasi-vscode/0.png'
	import VSCodeInstall1 from './assets/instalasi-vscode/1.png'
	import VSCodeInstall2 from './assets/instalasi-vscode/2.png'
	import VSCodeInstall3 from './assets/instalasi-vscode/3.png'
	import VSCodeInstall4 from './assets/instalasi-vscode/4.png'
	import VSCodeInstall5 from './assets/instalasi-vscode/5.png'
	import VSCodeInstall6 from './assets/instalasi-vscode/6.png'

	import VSCodeWelcome from './assets/vscode/welcome.png'
	import VSCodeOpenFolder from './assets/vscode/open-folder.png'
	import VSCodeTrust from './assets/vscode/trust.png'
	import VSCodeNewFile from './assets/vscode/create-file.png'

	import DemoTitle from './assets/demo/title.png'
</script>

<Presentation>
	<Vertical>
		<Slide animate>
			<Layout>
				<p class="font-bold">Pengenalan Visual Studio Code & Dasar HTML</p>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<p class="font-bold">Pengenalan Visual Studio Code & Dasar HTML</p>
				<div class="flex justify-center gap-2 w-full">
					<a href="https://en.wikipedia.org/wiki/HTML">
						<img src={HTMLIcon} alt="HTML" />
					</a>
					<a href="https://code.visualstudio.com/">
						<img src={VSCodeIcon} alt="VSCode" />
					</a>
				</div>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl" data-id="apa-yang-dipelajari">
					Apa saja yang akan kita pelajari?
				</h2>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl" data-id="apa-yang-dipelajari">
					Apa saja yang akan kita pelajari?
				</h2>
				<ul class="list-disc text-left flex flex-col gap-2 mt-8">
					<Step>
						<li>Download Visual Studio Code</li>
					</Step>
					<Step>
						<li>Instalasi Visual Studio Code</li>
					</Step>
					<Step>
						<li>Membuka Visual Studio Code</li>
					</Step>
					<Step>
						<li>Membuat & Membuka folder</li>
					</Step>
					<Step>
						<li>Membuat & Membuka file</li>
					</Step>
					<Step>
						<li>HTML paling dasar</li>
					</Step>
				</ul>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Apa yang kita buat</h2>
			</Layout>
		</Slide>
		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Apa yang kita buat</h2>
				<img src={PreviewIndex} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Apa yang kita buat</h2>
				<img src={PreviewDetail} alt="" />
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">
					Download Visual Studio Code
				</h2>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2>Kunjungi Halaman Download Visual Studio Code</h2>
				<img src={VSCodeInstall0} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Lakukan Instalasi</h2>
				<img src={VSCodeInstall1} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Lakukan Instalasi</h2>
				<img src={VSCodeInstall2} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Lakukan Instalasi</h2>
				<img src={VSCodeInstall3} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Lakukan Instalasi</h2>
				<img src={VSCodeInstall4} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Lakukan Instalasi</h2>
				<img src={VSCodeInstall5} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Lakukan Instalasi</h2>
				<img src={VSCodeInstall6} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Buka Visual Studio Code</h2>
				<img src={VSCodeWelcome} alt="" />
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">
					Membuka & Membuat Project di Visual Studio Code
				</h2>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<img src={VSCodeOpenFolder} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<img src={VSCodeTrust} alt="" />
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<img src={VSCodeNewFile} alt="" />
			</Layout>
		</Slide>

		<Slide>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Apakah ada pertanyaan?</h2>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Apa itu HTML</h2>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Apa itu HTML</h2>
				<p class="mt-4">
					HTML adalah bahasa markup yang telah distandarkan untuk ditampilkan
					dalam <span class="italic">browser</span>
				</p>

				<p class="mt-4">File HTML dapat di indentifikasikan dengan extensi</p>

				<Step>
					<code>.html</code>
				</Step>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Struktur HTML</h2>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Struktur HTML</h2>
				<Code lang="html" lines="|1|2,4">
					{`
					<!DOCTYPE html>
					<html>

					</html>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl">Struktur HTML</h2>
				<Code lang="html" lines="|4,6|8,11|5|9,10|">
					{`
					<!DOCTYPE html>
					<html>

					<head>
						<title>Daftar Manga</title>
					</head>

					<body>
						<h2>Daftar Manga</h2>
						<p>Ini website pertama ku</p>
					</body>

					</html>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<div class="bg-white h-[100vh] w-full text-left">
					<h2 class="text-5xl font-bold text-black">Daftar Manga</h2>
					<p class="text-base font-normal text-black">Ini website pertama ku</p>
				</div>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<Code lang="html">
					{`<h2> Content Disini </h2>`}
				</Code>
				<h2 class="text-5xl">Element</h2>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<Code lang="html">
					{`<h2> Content Disini </h2>`}
				</Code>
				<h2 class="text-5xl">Element</h2>
				<p class="text-4xl">
					Secara sederhana merupakan block utama dalam pembuatan suatu web, <span
						class="italic font-bold">Elemen</span
					>
					dapat memiliki elemen lagi didalamnya, pasti mempunyai
					<span class="italic font-bold">tag pembuka</span>
					dan hampir semua memakai
					<span class="italic font-bold">tag penutup</span>
					dan juga terdapat <span class="italic font-bold">attribute</span>
				</p>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<Code lang="html">
					{`<h2>`}
				</Code>
				<h2>Tag Pembuka</h2>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<Code lang="html">
					{`</h2>`}
				</Code>
				<h2>Tag Penutup</h2>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul Tab</h2>

				<p class="text-3xl">
					Suatu elemen yang digunakan untuk memberi nama pada tab
				</p>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul Tab</h2>
				<Code lang="html">
					{`<title>Daftar Manga</title>`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<img src={DemoTitle} alt="" class="w-screen" />
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>

				<p class="text-3xl">
					Suatu elemen yang digunakan untuk membuat dan merepresentasikan judul
				</p>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h1>Halo</h1>
					<h2>Halo</h2>
					<h3>Halo</h3>
					<h4>Halo</h4>
					<h5>Halo</h5>
					<h6>Halo</h6>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h1>Halo</h1>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h1>Halo</h1>
					`}
				</Code>

				<div class="bg-white h-[75vh] w-full text-left">
					<h1 class="text-7xl font-bold text-black">Halo</h1>
				</div>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h2>Halo</h2>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h2>Halo</h2>
					`}
				</Code>

				<div class="bg-white h-[75vh] w-full text-left">
					<h1 class="text-6xl font-bold text-black">Halo</h1>
				</div>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h3>Halo</h3>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h3>Halo</h3>
					`}
				</Code>

				<div class="bg-white h-[75vh] w-full text-left">
					<h1 class="text-5xl font-bold text-black">Halo</h1>
				</div>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h4>Halo</h4>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h4>Halo</h4>
					`}
				</Code>

				<div class="bg-white h-[75vh] w-full text-left">
					<h1 class="text-4xl font-bold text-black">Halo</h1>
				</div>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h5>Halo</h5>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h5>Halo</h5>
					`}
				</Code>

				<div class="bg-white h-[75vh] w-full text-left">
					<h1 class="text-3xl font-bold text-black">Halo</h1>
				</div>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h6>Halo</h6>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Judul / Heading</h2>
				<Code lang="html">
					{`
					<h6>Halo</h6>
					`}
				</Code>

				<div class="bg-white h-[75vh] w-full text-left">
					<h1 class="text-2xl font-bold text-black">Halo</h1>
				</div>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Paragraf</h2>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Paragraf</h2>
				<Code lang="html" lines="|1,6|2-5|8,10|9">
					{`
					<p>
						Lorem ipsum dolor sit amet consectetur adipisicing elit.
						Sapiente fuga dolores perferendis maxime commodi vero voluptate,
						nihil error aperiam obcaecati omnis ipsam possimus libero labore, dicta
						a nostrum est praesentium.
					</p>

					<p>
						AAAAAA
					</p>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<div class="bg-white h-[75vh] w-full text-left">
					<p class="text-black text-base">
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente
						fuga dolores perferendis maxime commodi vero voluptate, nihil error
						aperiam obcaecati omnis ipsam possimus libero labore, dicta a
						nostrum est praesentium.
					</p>

					<p class="text-black text-base">AAAAAA</p>
				</div>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Tengah</h2>

				<p class="text-3xl">
					Suatu elemen yang digunakan untuk menengahkan suatu element
				</p>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Tengah</h2>

				<Code lang="html" lines="|1,5|2-4">
					{`
					<center>
						<h1>
							AAAAAA
						</h1>
					</center>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="text-5xl">Element Tengah</h2>

				<Code lang="html" lines="|1,5|2-4">
					{`
					<center>
						<h1>
							AAAAAA
						</h1>
					</center>
					`}
				</Code>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<div class="bg-white h-[75vh] w-full text-left">
					<center class="text-7xl font-bold text-black">
						<h1>AAAAAA</h1>
					</center>
				</div>
			</Layout>
		</Slide>
	</Vertical>

	<Vertical>
		<Slide animate>
			<Layout>
				<Code lang="html" lines="|1|2|25|4,6|5|8|23|9-22">
					{`
					<!DOCTYPE html>
					<html>

					<head>
						<title>Daftar Manga</title>
					</head>

					<body>
						<center>
							<h1>Daftar Manga</h1>
						</center>
						<p>
							Lorem ipsum dolor sit amet consectetur adipisicing elit.
							Sapiente fuga dolores perferendis maxime commodi vero voluptate,
							nihil error aperiam obcaecati omnis ipsam possimus libero labore, dicta
							a nostrum est praesentium.

							Lorem ipsum dolor sit amet consectetur adipisicing elit.
							Sapiente fuga dolores perferendis maxime commodi vero voluptate,
							nihil error aperiam obcaecati omnis ipsam possimus libero labore, dicta
							a nostrum est praesentium.
						</p>
					</body>

					</html>
					`}
				</Code>
			</Layout>
		</Slide>
	</Vertical>
</Presentation>

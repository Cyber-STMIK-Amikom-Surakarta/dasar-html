<script lang="ts">
	import { Presentation, Slide, Vertical, Layout } from '@components'

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
				<ul class="list-disc text-left flex flex-col gap-2 mt-2">
					<li>Download Visual Studio Code</li>
				</ul>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl" data-id="apa-yang-dipelajari">
					Apa saja yang akan kita pelajari?
				</h2>
				<ul class="list-disc text-left flex flex-col gap-2 mt-2">
					<li>Download Visual Studio Code</li>
					<li>Instalasi Visual Studio Code</li>
				</ul>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl" data-id="apa-yang-dipelajari">
					Apa saja yang akan kita pelajari?
				</h2>
				<ul class="list-disc text-left flex flex-col gap-2 mt-2">
					<li>Download Visual Studio Code</li>
					<li>Instalasi Visual Studio Code</li>
					<li>Membuka Visual Studio Code</li>
				</ul>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl" data-id="apa-yang-dipelajari">
					Apa saja yang akan kita pelajari?
				</h2>
				<ul class="list-disc text-left flex flex-col gap-2 mt-8">
					<li>Download Visual Studio Code</li>
					<li>Instalasi Visual Studio Code</li>
					<li>Membuka Visual Studio Code</li>
					<li>Membuat & Membuka folder</li>
				</ul>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl" data-id="apa-yang-dipelajari">
					Apa saja yang akan kita pelajari?
				</h2>
				<ul class="list-disc text-left flex flex-col gap-2 mt-8">
					<li>Download Visual Studio Code</li>
					<li>Instalasi Visual Studio Code</li>
					<li>Membuka Visual Studio Code</li>
					<li>Membuat & Membuka folder</li>
					<li>Membuat & Membuka file</li>
				</ul>
			</Layout>
		</Slide>

		<Slide animate>
			<Layout>
				<h2 class="font-mono font-bold text-5xl" data-id="apa-yang-dipelajari">
					Apa saja yang akan kita pelajari?
				</h2>
				<ul class="list-disc text-left flex flex-col gap-2 mt-8">
					<li>Download Visual Studio Code</li>
					<li>Instalasi Visual Studio Code</li>
					<li>Membuka Visual Studio Code</li>
					<li>Membuat & Membuka folder</li>
					<li>Membuat & Membuka file</li>
					<li>HTML paling dasar</li>
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
			</Layout>
		</Slide>
	</Vertical>
</Presentation>

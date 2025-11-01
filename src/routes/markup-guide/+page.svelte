{#snippet thead()}
	<thead>
		<tr class="">
			<th
				><div class="flex h-10 w-10 items-center rounded-full bg-blue-200">
					<p class="w-full text-center">DF</p>
				</div></th
			>
			<th
				><div class="flex h-10 w-10 items-center rounded-full bg-red-200">
					<p class="w-full text-center">LF</p>
				</div></th
			>
			<th>Description</th>
		</tr>
	</thead>
{/snippet}

<h1 class="mb-20! h1">Transcription guide</h1>
<table class="mx-auto mt-10 w-full text-left">
	{@render thead()}
	<tbody>
		<!-- Section -->
		<tr><th><h3 class="mt-2 h5">Insertions by Ceresa</h3></th></tr>
		<tr>
			<th data-fassung="DF">Alice <hand>Ceresa</hand></th>
			<th data-fassung="LF">Alice <hand>Ceresa</hand></th>
			<th>Manuscript text in a typoscript</th></tr
		>
		<tr>
			<th data-fassung="DF">Alice <strikeH>Ceresa</strikeH></th>
			<th data-fassung="LF">Alice <strikeH>Ceresa</strikeH></th>
			<th>Crossed out by hand</th></tr
		>
		<tr>
			<th data-fassung="DF">Alice <strikeT>Ceresa</strikeT></th>
			<th data-fassung="LF">Alice <strikeT>Ceresa</strikeT></th>
			<th>Crossed out with the typewriter</th></tr
		>
		<tr>
			<th data-fassung="DF">Alice <insAbove>Ceresa</insAbove></th>
			<th data-fassung="LF">Alice <insAbove>Ceresa</insAbove></th>
			<th>Insertions above the line</th></tr
		>
		<tr>
			<th data-fassung="DF">Alice <insBelow>Ceresa</insBelow></th>
			<th data-fassung="LF">Alice <insBelow>Ceresa</insBelow></th>
			<th>Insertions below the line by hand</th></tr
		>
		<tr>
			<th data-fassung="DF">Alice <insInline>Ceresa</insInline></th>
			<th data-fassung="LF">Alice <insInline>Ceresa</insInline></th>
			<th>Insertions within the line</th></tr
		>

		<tr>
			<th data-fassung="DF">Alice <insMargin>Ceresa</insMargin></th>
			<th data-fassung="LF">Alice <insMargin>Ceresa</insMargin></th>
			<th>Insertions in the margin</th></tr
		>

		<!-- Section -->
		<tr><th><h3 class="mt-2 h5">Replacements by Ceresa</h3></th></tr>
		<tr>
			<th data-fassung="DF"><replAbove data-hand><old>Alice</old> <new>Ceresa</new></replAbove></th>
			<th data-fassung="LF"><replAbove data-hand><old>Alice</old> <new>Ceresa</new></replAbove></th>
			<th>«Ceresa» replaces «Alice» above the line by hand</th></tr
		>
		<tr>
			<th data-fassung="DF"><replBelow data-hand><old>Alice</old> <new>Ceresa</new></replBelow></th>
			<th data-fassung="LF"><replBelow data-hand><old>Alice</old> <new>Ceresa</new></replBelow></th>
			<th>«Ceresa» replaces «Alice» below the line by hand</th></tr
		>
		<tr>
			<th data-fassung="DF"><replInline><old>Alice</old> <new>Ceresa</new></replInline></th>
			<th data-fassung="LF"><replInline><old>Alice</old> <new>Ceresa</new></replInline></th>
			<th>«Ceresa» replaces «Alice» within the line with typewriter</th></tr
		>
		<tr>
			<th data-fassung="DF"
				><replInline data-hand><old>Alice</old> <new>Ceresa</new></replInline></th
			>
			<th data-fassung="LF"
				><replInline data-hand><old>Alice</old> <new>Ceresa</new></replInline></th
			>
			<th>«Ceresa» replaces «Alice» within the line by hand</th></tr
		>

		<tr>
			<th data-fassung="DF"><replOver data-hand><old>Alice</old> <new>Ceresa</new></replOver></th>
			<th data-fassung="LF"><replOver data-hand><old>Alice</old> <new>Ceresa</new></replOver></th>
			<th>«Ceresa» written over «Alice» by hand</th></tr
		>
		<tr>
			<th data-fassung="DF"><replOver><old>Alice</old> <new>Ceresa</new></replOver></th>
			<th data-fassung="LF"><replOver><old>Alice</old> <new>Ceresa</new></replOver></th>
			<th>«Ceresa» written over «Alice» with typewriter</th></tr
		>
		<tr>
			<th data-fassung="DF"><replMargin><old>Alice</old> <new>Ceresa</new></replMargin></th>
			<th data-fassung="LF"><replMargin><old>Alice</old> <new>Ceresa</new></replMargin></th>
			<th>«Ceresa» replaces «Alice» in the margin</th></tr
		>

		<!-- Section -->
		<tr><th><h3 class="mt-2 h5">Repositioning by Ceresa</h3></th></tr>

		<tr>
			<th data-fassung="DF"
				><movedBlockRef data-ref="1" />Alice
				<movedBlock data-ref="1" data-label="Paragrafo riposizionato">Ceresa</movedBlock></th
			>
			<th data-fassung="LF"
				><movedBlockRef data-ref="1" />Alice
				<movedBlock data-ref="1" data-label="Paragrafo riposizionato">Ceresa</movedBlock></th
			>
		</tr>

		<!-- Section -->
		<tr><th><h3 class="mt-2 h5">Editorial Interventions</h3></th></tr>

		<tr>
			<th data-fassung="DF">Alice Ceres<insEditorial>a</insEditorial></th>
			<th data-fassung="LF">Alice Ceres<insEditorial>a</insEditorial></th>
			<th>Editorial insertion</th></tr
		>
		<tr>
			<th data-fassung="DF">Ali<uncertain>?</uncertain> Ceresa</th>
			<th data-fassung="LF">Ali<uncertain>?</uncertain> Ceresa</th>
			<th>Uncertain reading</th></tr
		>
		<tr>
			<th data-fassung="DF">Alice <illegible>xxx</illegible> Ceresa</th>
			<th data-fassung="LF">Alice <illegible>xxx</illegible> Ceresa</th>
			<th>Illegible word (1 x = approx. 1 letter)</th></tr
		>
	</tbody>
</table>

<h1 class="mt-30 mb-20! h1">Semantic Annotations</h1>
<table class="mx-auto mt-10 w-full text-left">
	<thead></thead>
	<tbody>
		<tr
			><th class="font-bold! italic"
				>Different combinations to get a feel about what's possible. Of course we should choose one
				of the options.</th
			></tr
		>
		<tr>
			<th data-fassung="DF">This is how <a data-place href="">places</a> are highlighted.</th></tr
		>
		<tr
			><th data-fassung="DF">This is how <a data-person href="">people</a> are highlighted.</th></tr
		>
		<tr
			><th data-fassung="DF"
				>This is how <a data-publisher href="">publishing houses</a> are highlighted.</th
			></tr
		>
		<tr><th data-fassung="DF">This is how <a data-work href="">Works</a> are highlighted.</th></tr>
	</tbody>
</table>

<style>
	@reference "tailwindcss";
	thead th {
		@apply px-4 py-2 font-bold;
	}
	tbody th {
		@apply px-4 py-2 font-normal;
	}
</style>

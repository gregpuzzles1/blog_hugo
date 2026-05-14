---
title: "Greg's Reading List"
date: 2026-05-01
draft: false
description: "A personal reading list with book covers, notes, and ratings."
---

Welcome to Greg's Reading List. Books I've read, loved and am working through.

<style>
section.prose {
	width: 100%;
	max-width: 100% !important;
}

.prose > div.min-w-0.min-h-0.max-w-fit {
	width: 100%;
	max-width: 100%;
}

.article-content {
	max-width: 100% !important;
}

.reading-grid {
	display: grid;
	grid-template-columns: repeat(1, minmax(0, 1fr));
	gap: 1.25rem;
	margin: 1.25rem auto 0;
	width: 100%;
	max-width: 1600px;
	padding-left: clamp(0.5rem, 2vw, 1rem);
	padding-right: clamp(0.5rem, 2vw, 1rem);
	box-sizing: border-box;
}

.reading-card {
	margin: 0;
	display: flex;
	flex-direction: column;
	overflow: hidden;
	border-radius: 12px;
	border: 1px solid #025940;
	background: #026873;
	box-shadow: 0 4px 12px rgba(2, 64, 89, 0.45);
	transition: transform 0.22s ease, box-shadow 0.22s ease;
}

.reading-card:hover {
	transform: translateY(-6px);
	box-shadow: 0 12px 36px rgba(4, 191, 138, 0.22), 0 4px 12px rgba(2, 64, 89, 0.5);
}

.book-cover {
	width: 100%;
	aspect-ratio: 2 / 3;
	object-fit: cover;
	display: block;
	background: #024059;
}

.book-meta {
	display: grid;
	grid-template-rows: repeat(6, minmax(0, auto));
	margin: auto 0 0;
	padding: 0.65rem 0.9rem 0.85rem;
	border-top: 1px solid rgba(2, 89, 64, 0.5);
	background: rgba(2, 64, 89, 0.35);
	font-size: 0.78rem;
	line-height: 1.35;
	color: rgba(232, 244, 240, 0.82);
	min-height: 10.2rem;
	align-content: start;
}

.book-meta-line {
	display: block;
	line-height: 1.35rem;
	min-height: 1.35rem;
	white-space: nowrap;
	overflow: hidden;
	text-overflow: ellipsis;
}

.book-meta-line + .book-meta-line {
	margin-top: 0.18rem;
}

.book-meta-label {
	font-weight: 700;
	color: #04BF8A;
}

.book-title {
	margin: 0;
	padding: 0.65rem 0.9rem 0;
	font-size: 0.9rem;
	line-height: 1.25;
	font-weight: 700;
	color: #e8f4f0;
	min-height: 2.6rem;
	display: -webkit-box;
	-webkit-line-clamp: 2;
	-webkit-box-orient: vertical;
	overflow: hidden;
}

.book-meta.clm-meta {
	grid-template-rows: repeat(2, minmax(0, auto));
	min-height: auto;
	padding-top: 0.45rem;
}

@media (min-width: 640px) {
	.reading-grid {
		grid-template-columns: repeat(2, minmax(0, 1fr));
	}
}

@media (min-width: 900px) {
	.reading-grid {
		grid-template-columns: repeat(3, minmax(0, 1fr));
	}
}

@media (min-width: 1200px) {
	.reading-grid {
		grid-template-columns: repeat(4, minmax(0, 1fr));
	}
}

@media (min-width: 1650px) {
	.reading-grid {
		grid-template-columns: repeat(5, minmax(0, 1fr));
	}
}

@media (max-width: 480px) {
	.reading-grid {
		grid-template-columns: repeat(2, minmax(0, 1fr));
		gap: 1rem;
		padding-left: 0.35rem;
		padding-right: 0.35rem;
	}

	.book-meta {
		font-size: 0.73rem;
		padding: 0.55rem 0.7rem 0.7rem;
		min-height: 9.7rem;
	}

	.book-meta-line {
		line-height: 1.25rem;
		min-height: 1.25rem;
	}
}
</style>

{{< tabs >}}
{{< tab label="Books" md="false" >}}
<div class="reading-grid">
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/23_TheAdventuresofPinocchio.jpg" alt="Cover of The Adventures of Pinocchio by Carlo Collodi">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Adventures of Pinocchio</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Carlo Collodi</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1883</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Children's Fantasy, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> On my reading list</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> Not rated yet</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/22_TheMinistryofHealing.jpg" alt="Cover of The Ministry of Healing by Ellen G. White">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Ministry of Healing</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Ellen G. White</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1905</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Christian Living</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Spring 2026</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/21_AMidsummerNightsDream.jpg" alt="Cover of A Midsummer Night's Dream by William Shakespeare">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> A Midsummer Night's Dream</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> William Shakespeare</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1600</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Comedy, Fiction</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Summer 2025</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/20_LostonPurpose.jpg" alt="Cover of Lost on Purpose by Patrick Taylor">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Lost on Purpose</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Patrick Taylor</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 2015</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Non-Fiction Adventure Narrative</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Spring 2025</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/19_Frankenstein.jpg" alt="Cover of Frankenstein by Mary Shelley">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Frankenstein</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Mary Shelley</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1818</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Gothic Novel</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Winter 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/18_TheThreeMusketeers.jpg" alt="Cover of The Three Musketeers by Alexandre Dumas">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Three Musketeers</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Alexandre Dumas</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1844</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Historical Adventure, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Summer 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/17_ThePictureofDorianGray.jpg" alt="Cover of The Picture of Dorian Gray by Oscar Wilde">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Picture of Dorian Gray</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Oscar Wilde</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1890</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Gothic Novel</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Summer 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/16_ThePickwickPapers.jpg" alt="Cover of The Pickwick Papers by Charles Dickens">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Pickwick Papers</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Charles Dickens</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1837</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Classic Novel</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Spring 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/15_BlackBeauty.jpg" alt="Cover of Black Beauty by Anna Sewell">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Black Beauty</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Anna Sewell</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1877</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Classic Novel</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Spring 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/14_MollFlanders.jpg" alt="Cover of Moll Flanders by Daniel Defoe">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Moll Flanders</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Daniel Defoe</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1722</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Classic Historical Fiction</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Spring 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/13_FairyTales.jpg" alt="Cover of Fairy Tales by Hans Andersen">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Fairy Tales</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Hans Andersen</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1835</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Collection of Fairy Tales, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Winter 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/12_RobinsonCrusoe.jpg" alt="Cover of Robinson Crusoe by Daniel Defoe">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Robinson Crusoe</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Daniel Defoe</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1719</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Adventure Novel, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Winter 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/11_TheWonderfulWizardofOz.jpg" alt="Cover of The Wonderful Wizard of Oz by L. Frank Baum">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Wonderful Wizard of Oz</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> L. Frank Baum</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1900</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Fantasy Novel, Children's Classic</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Winter 2024</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/10_PilgrimsProgress.jpg" alt="Cover of The Pilgrim's Progress by John Bunyan">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Pilgrim's Progress</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> John Bunyan</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1678</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Christian Allegory</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Winter 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/09_TreasureIsland.jpg" alt="Cover of Treasure Island by Robert Louis Stevenson">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Treasure Island</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Robert Louis Stevenson</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1882</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Adventure Novel, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Fall 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/08_TheRedBadgeofCourage.jpg" alt="Cover of The Red Badge of Courage by Stephen Crane">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Red Badge of Courage</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Stephen Crane</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1895</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> War Novel, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Fall 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/07_AlicesAdventuresinWonderland.jpg" alt="Cover of Alice's Adventures in Wonderland by Lewis Carroll">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Alice's Adventures in Wonderland</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Lewis Carroll</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1865</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Children's Fantasy Classic</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Fall 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/06_AroundtheWorldinEightyDays.jpg" alt="Cover of Around the World in Eighty Days by Jules Verne">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Around the World in Eighty Days</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Jules Verne</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1872</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Adventure Novel, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Summer 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/05_UncleTomsCabin.jpg" alt="Cover of Uncle Tom's Cabin by Harriet Beecher Stowe">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Uncle Tom's Cabin</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Harriet Beecher Stowe</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1852</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Classic Historical Fiction Novel</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Summer 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/04_TheLastoftheMohicians.jpg" alt="Cover of The Last of the Mohicans by James Fenimore Cooper">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Last of the Mohicans</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> James Fenimore Cooper</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1826</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> History Fiction Adventure Novel, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Summer 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/03_TheTimeMachine.jpg" alt="Cover of The Time Machine by H. G. Wells">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Time Machine</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> H. G. Wells</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1895</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Science Fiction Classic</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Summer 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/02_TheCalloftheWild.jpg" alt="Cover of The Call of the Wild by Jack London">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Call of the Wild</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Jack London</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1903</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Adventure Novel, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Summer 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐⭐</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/books/01_Moby-Dick.jpg" alt="Cover of Moby-Dick by Herman Melville">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Moby-Dick</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Herman Melville</span>
			<span class="book-meta-line"><span class="book-meta-label">Originally Published:</span> 1851</span>
			<span class="book-meta-line"><span class="book-meta-label">Genre:</span> Adventure Novel, Classic Literature</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Spring 2023</span>
			<span class="book-meta-line"><span class="book-meta-label">Rating:</span> ⭐⭐⭐⭐</span>
		</div>
	</article>
</div>
{{< /tab >}}
{{< tab label="Audio Books" md="false" >}}
<div class="reading-grid">
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/32_LandscapesoftheSoul.jpg" alt="Landscapes of the Soul by Syd &amp; Geoff Holsclaw">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Landscapes of the Soul</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Syd &amp; Geoff Holsclaw</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> Currently reading</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/31_TheMountainisYou.jpg" alt="Cover of The Mountain is You by Brianna Wiest">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Mountain is You</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Brianna Wiest</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2025</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/30_Co-Intelligence.jpg" alt="Cover of Co-Intelligence by Ethan Mollick">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Co-Intelligence</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Ethan Mollick</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2025</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/29_TheDigitalMindset.jpg" alt="Cover of The Digital Mindset by Paul Leonardi &amp; Tsedal Neeley">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Digital Mindset</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Paul Leonardi &amp; Tsedal Neeley</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2024</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/28_StaySaneinanInsaneWorld.jpg" alt="Cover of Stay Sane in an Insane World by Greg Harden">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Stay Sane in an Insane World</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Greg Harden</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2023</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/27_DigitalMinimalism.jpg" alt="Cover of Digital Minimalism by Cal Newport">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Digital Minimalism</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Cal Newport</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2022</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/26_TheDataDetective.jpg" alt="Cover of The Data Detective by Tim Harford">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Data Detective</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Tim Harford</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2021</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/25_UnderaWhiteSkyTheNatureoftheFuture.jpg" alt="Cover of Under a White Sky: The Nature of the Future by Elizabeth Kolbert">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Under a White Sky</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Elizabeth Kolbert</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2021</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/24_TheMythofExperience.jpg" alt="Cover of The Myth of Experience by Emre Soyer and Robin M. Hogarth">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Myth of Experience</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Emre Soyer &amp; Robin M. Hogarth</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2021</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/23_HumorSeriously.jpg" alt="Cover of Humor, Seriously by Jennifer Aaker &amp; Naomi Bagdonas">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Humor, Seriously</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Jennifer Aaker &amp; Naomi Bagdonas</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2021</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/22_Abundance.jpg" alt="Cover of Abundance by Peter H. Diamandis &amp; Steven Kotler">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Abundance</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Peter H. Diamandis &amp; Steven Kotler</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/21_Blackout.jpg" alt="Cover of Blackout by Candace Owens">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Blackout</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Candace Owens</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/20_SeaStories.jpg" alt="Cover of Sea Stories by William H. McRaven">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Sea Stories</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> William H. McRaven</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/19_TheInfiniteGame.jpg" alt="Cover of The Infinite Game by Simon Sinek">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Infinite Game</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Simon Sinek</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/18_Range.jpg" alt="Cover of Range by David Epstein">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Range</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> David Epstein</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/17_IdentityTheft.jpg" alt="Cover of Identity Theft by Ron Cantor">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Identity Theft</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Ron Cantor</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/16_1776.jpg" alt="Cover of 1776 by David McCullough">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> 1776</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> David McCullough</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/15_Upstream.jpg" alt="Cover of Upstream by Dan Heath">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Upstream</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Dan Heath</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/14_HowtoStopWorryingandStartLiving.jpg" alt="Cover of How to Stop Worrying and Start Living by Dale Carnegie">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> How to Stop Worrying and Start Living</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Dale Carnegie</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/13_ThePrayerCoin.jpg" alt="Cover of The Prayer Coin by Elisa Morgan">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Prayer Coin</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Elisa Morgan</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/12_TalkingtoStrangers.jpg" alt="Cover of Talking to Strangers by Malcolm Gladwell">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Talking to Strangers</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Malcolm Gladwell</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/11_TheWrightBrothers.jpg" alt="Cover of The Wright Brothers by David McCullough">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Wright Brothers</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> David McCullough</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2020</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/10_TheCultureCode.jpg" alt="Cover of The Culture Code by Daniel Coyle">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Culture Code</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Daniel Coyle</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/09_TheSoulofaTeam.jpg" alt="Cover of The Soul of a Team by Tony Dungy">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Soul of a Team</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Tony Dungy</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/08ThePioneers.jpg" alt="Cover of The Pioneers by David McCullough">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Pioneers</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> David McCullough</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/07_WeaponsofMathDestruction.jpg" alt="Cover of Weapons of Math Destruction by Cathy O&#39;Neil">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Weapons of Math Destruction</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Cathy O&#39;Neil</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/06_ThisistheDay.jpg" alt="Cover of This is The Day by Tim Tebow">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> This is The Day</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Tim Tebow</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/05_DavidandGoliath.jpg" alt="Cover of David and Goliath by Malcolm Gladwell">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> David and Goliath</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Malcolm Gladwell</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/04_MakeYourBed.jpg" alt="Cover of Make Your Bed by William H. McRaven">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Make Your Bed</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> William H. McRaven</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/03_Ketofast.jpg" alt="Cover of Ketofast by Dr. Joseph Mercola">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Ketofast</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Dr. Joseph Mercola</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/02_TheAgingBrain.jpg" alt="Cover of The Aging Brain by Timothy R. Jennings, MD">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> The Aging Brain</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Timothy R. Jennings, MD</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/audio_books/01_Shaken.jpg" alt="Cover of Shaken by Tim Tebow">
		<div class="book-meta">
			<span class="book-meta-line"><span class="book-meta-label">Title:</span> Shaken</span>
			<span class="book-meta-line"><span class="book-meta-label">Author:</span> Tim Tebow</span>
			<span class="book-meta-line"><span class="book-meta-label">Date Read:</span> 2019</span>
		</div>
	</article>
</div>
{{< /tab >}}
{{< tab label="CLM Books" md="false" >}}
<div class="reading-grid">
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/01 Encountering the Living God.jpg" alt="Cover of 1 Encountering the Living God">
		<h3 class="book-title">1 Encountering the Living God</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 115</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 3.09 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> encountering, living</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/01-Encountering-the-Living-God.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/01-Encountering-the-Living-God.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/02 Practicing the Means of Grace.jpg" alt="Cover of 2 Practicing the Means of Grace">
		<h3 class="book-title">2 Practicing the Means of Grace</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 88</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.42 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> practicing, means</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/02-Practicing-the-Means-of-Grace.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/02-Practicing-the-Means-of-Grace.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/03 Pursuing a Holy Lifestyle.jpg" alt="Cover of 3 Pursuing a Holy Lifestyle">
		<h3 class="book-title">3 Pursuing a Holy Lifestyle</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 85</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 1.28 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> pursuing, holy</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/03-Pursuing-a-Holy-Lifestyle.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/03-Pursuing-a-Holy-Lifestyle.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/04 Battling Life's Multiple Temptations.jpg" alt="Cover of 4 Battling Life&#x27;s Multiple Temptations">
		<h3 class="book-title">4 Battling Life&#x27;s Multiple Temptations</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 89</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 1.49 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> battling, multiple</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/04-Battling-Lifes-Multiple-Temptations.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/04-Battling-Lifes-Multiple-Temptations.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/05 Practicing the Presence of God.jpg" alt="Cover of 5 Practicing the Presence of God">
		<h3 class="book-title">5 Practicing the Presence of God</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 86</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.21 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> practicing, presence</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/05-Practicing-the-Presence-of-God.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/05-Practicing-the-Presence-of-God.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/06 Overcoming Obstacles to Christian Growth.jpg" alt="Cover of 6 Overcoming Obstacles to Christian Growth">
		<h3 class="book-title">6 Overcoming Obstacles to Christian Growth</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 92</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.57 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> overcoming, obstacles</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/06-Overcoming-Obstacles-to-Christian-Growth.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/06-Overcoming-Obstacles-to-Christian-Growth.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/07 Refocusing on Lifes Priorities.jpg" alt="Cover of 7 Refocusing on Lifes Priorities">
		<h3 class="book-title">7 Refocusing on Lifes Priorities</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 91</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.50 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> refocusing, lifes</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/07-Refocusing-on-Lifes-Priorities.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/07-Refocusing-on-Lifes-Priorities.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/08 Appropriating the Power of Prayer and Faith.jpg" alt="Cover of 8 Appropriating the Power of Prayer and Faith">
		<h3 class="book-title">8 Appropriating the Power of Prayer and Faith</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 82</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.39 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> appropriating, power</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/08-Appropriating-the-Power-of-Prayer-and-Faith.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/08-Appropriating-the-Power-of-Prayer-and-Faith.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/09 Mainting Life's Various Stewardship.jpg" alt="Cover of 9 Mainting Life&#x27;s Various Stewardship">
		<h3 class="book-title">9 Mainting Life&#x27;s Various Stewardship</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 86</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 1.53 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> mainting, various</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/09-Maintaining-Lifes-Various-Stewardship.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/09-Maintaining-Lifes-Various-Stewardship.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/10 Rescuing the Lost Ones.jpg" alt="Cover of 10 Rescuing the Lost Ones">
		<h3 class="book-title">10 Rescuing the Lost Ones</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 96</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.85 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> rescuing, lost</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/10-Rescuing-the-Lost-Ones.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/10-Rescuing-the-Lost-Ones.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/11 Reaching Out in Holy Love.jpg" alt="Cover of 11 Reaching Out in Holy Love">
		<h3 class="book-title">11 Reaching Out in Holy Love</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 85</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 1.36 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> reaching, out</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/11-Reaching-Out-in-Holy-Love.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/11-Reaching-Out-in-Holy-Love.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/12 Surviving Lifes Hard Trials.jpg" alt="Cover of 12 Surviving Lifes Hard Trials">
		<h3 class="book-title">12 Surviving Lifes Hard Trials</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 90</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.57 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> surviving, lifes</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/12-Surviving-Lifes-Hard-Trials.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/12-Surviving-Lifes-Hard-Trials.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/13 Maintaining the Life of Faith.jpg" alt="Cover of 13 Maintaining the Life of Faith">
		<h3 class="book-title">13 Maintaining the Life of Faith</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 123</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 3.88 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> maintaining, faith</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/13-Maintaining-the-Life-of-Faith.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/13-Maintaining-the-Life-of-Faith.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Adventures in Biblical Faith.jpg" alt="Cover of Adventures in Biblical Faith">
		<h3 class="book-title">Adventures in Biblical Faith</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 573</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 46.45 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> adventures, biblical</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Adventures-in-Biblical-Faith.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Adventures-in-Biblical-Faith.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Am I My Brothers Keeper.jpg" alt="Cover of Am I My Brothers Keeper">
		<h3 class="book-title">Am I My Brothers Keeper</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 84</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 4.53 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> brothers, keeper</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Am-I-My-Brothers-Keeper.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Am-I-My-Brothers-Keeper.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/And Jesus Taught Them Saying.jpg" alt="Cover of And Jesus Taught Them Saying">
		<h3 class="book-title">And Jesus Taught Them Saying</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 296</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 296.85 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> jesus, taught</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/And-Jesus-Taught-Them-Saying.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/And-Jesus-Taught-Them-Saying.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Becoming Mature Christian.jpg" alt="Cover of Becoming Mature Christian">
		<h3 class="book-title">Becoming Mature Christian</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 127</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 14.21 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> becoming, mature</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Becoming-a-Mature-Christian.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Becoming-a-Mature-Christian.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/COME HOLY SPIRIT.jpg" alt="Cover of “COME HOLY SPIRIT”">
		<h3 class="book-title">“COME HOLY SPIRIT”</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 109</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 0.73 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> come, holy</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/COME-HOLY-SPIRIT.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/COME-HOLY-SPIRIT.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Conquering the Enemies Within.jpg" alt="Cover of Conquering the Enemies Within">
		<h3 class="book-title">Conquering the Enemies Within</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 127</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 5.36 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> conquering, enemies</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Conquering-the-Enemies-Within.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Conquering-the-Enemies-Within.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Cultivating Christ Like Character.jpg" alt="Cover of Cultivating Christ Like Character">
		<h3 class="book-title">Cultivating Christ Like Character</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 222</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 62.16 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> cultivating, christ</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Cultivating-Christ-Like-Character.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Cultivating-Christ-Like-Character.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Glimpses Into Reality.jpg" alt="Cover of Glimpses Into Reality">
		<h3 class="book-title">Glimpses Into Reality</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 479</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.95 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> glimpses, reality</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Glimpses-Into-Reality.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Glimpses-Into-Reality.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/God For All Seasons.jpg" alt="Cover of God For All Seasons">
		<h3 class="book-title">God For All Seasons</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 331</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 21.76 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> all, seasons</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/God-For-All-Seasons.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/God-For-All-Seasons.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/How to Obtain and Maintain Eternal Salvation.jpg" alt="Cover of How to Obtain and Maintain Eternal Salvation">
		<h3 class="book-title">How to Obtain and Maintain Eternal Salvation</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 333</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 10.60 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> how, obtain</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/How-to-Obtain-and-Maintain-Eternal-Salvation.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/How-to-Obtain-and-Maintain-Eternal-Salvation.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/How Wide is God's Mercy.jpg" alt="Cover of How Wide is God&#x27;s Mercy">
		<h3 class="book-title">How Wide is God&#x27;s Mercy</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 75</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 52.03 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> how, wide</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/How-Wide-is-Gods-Mercy.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/How-Wide-is-Gods-Mercy.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Jesus The Great 'I Am'.jpg" alt="Cover of Jesus The Great &#x27;I Am&#x27;">
		<h3 class="book-title">Jesus The Great &#x27;I Am&#x27;</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 192</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 187.58 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> jesus, great</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Jesus-The-Great-I-Am.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Jesus-The-Great-I-Am.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Let Us Hold Fast.jpg" alt="Cover of Let Us Hold Fast">
		<h3 class="book-title">Let Us Hold Fast</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 391</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 51.90 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> let, hold</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Let-Us-Hold-Fast.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Let-Us-Hold-Fast.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Living the Life of Joy!.jpg" alt="Cover of Living the Life of Joy!">
		<h3 class="book-title">Living the Life of Joy!</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 220</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 6.75 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> living, joy</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Living-the-Life-of-Joy.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Living-the-Life-of-Joy.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Lost in Wonder, Love and Praise!.jpg" alt="Cover of Lost in Wonder, Love and Praise!">
		<h3 class="book-title">Lost in Wonder, Love and Praise!</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 262</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 8.69 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> lost, wonder</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Lost-in-Wonder-Love-and-Praise.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Lost-in-Wonder-Love-and-Praise.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Marks of a High Calling.jpg" alt="Cover of Marks of a High Calling">
		<h3 class="book-title">Marks of a High Calling</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 198</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 2.15 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> marks, high</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Marks-of-a-High-Calling.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Marks-of-a-High-Calling.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/Mountain Peaks of Salvation History.jpg" alt="Cover of Mountain Peaks of Salvation History">
		<h3 class="book-title">Mountain Peaks of Salvation History</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 67</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 32.98 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> mountain, peaks</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Mountain-Peaks-of-Salvation-History.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/Mountain-Peaks-of-Salvation-History.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/OUR FATHER WHO ART IN HEAVEN 1-9.jpg" alt="Cover of “OUR FATHER WHO ART IN HEAVEN”">
		<h3 class="book-title">“OUR FATHER WHO ART IN HEAVEN”</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 86</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 0.78 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> father, faith</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/OUR-FATHER-WHO-ART-IN-HEAVEN-1-9.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/OUR-FATHER-WHO-ART-IN-HEAVEN-1-9.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/The Balanced Life of Stewardship.jpg" alt="Cover of The Balanced Life of Stewardship">
		<h3 class="book-title">The Balanced Life of Stewardship</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 313</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 17.90 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> balanced, stewardship</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/The-Balanced-Life-of-Stewardship.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/The-Balanced-Life-of-Stewardship.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/The Marks of a Great Church.jpg" alt="Cover of The Marks of a Great Church">
		<h3 class="book-title">The Marks of a Great Church</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 257</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 29.93 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> marks, great</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/The-Marks-of-a-Great-Church.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/The-Marks-of-a-Great-Church.pdf" download>Download</a></span>
		</div>
	</article>
	<article class="reading-card">
		<img class="book-cover" src="/blog_hugo/images/CLMBooks/United in Christ.jpg" alt="Cover of United in Christ">
		<h3 class="book-title">United in Christ</h3>
		<div class="book-meta clm-meta">
			<span class="book-meta-line"><span class="book-meta-label">Pages:</span> 274</span>
			<span class="book-meta-line"><span class="book-meta-label">Size:</span> 254.89 MB</span>
			<span class="book-meta-line"><span class="book-meta-label">Keywords:</span> united, christ</span>
			<span class="book-meta-line"><a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/United-in-Christ.pdf" target="_blank" rel="noopener noreferrer">View</a> | <a href="https://pdfs.techtrailpulse.com/clmbooks/20260512/United-in-Christ.pdf" download>Download</a></span>
		</div>
	</article>
</div>
{{< /tab >}}
{{< /tabs >}}


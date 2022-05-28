---
title: How to choose your new laptop
description: Getting the right knowledge and tools to easily select your new laptop.
comments: true
hide: true
toc: false
layout: post
categories: [hardware, laptop]
image: https://images.unsplash.com/photo-1593642531955-b62e17bdaa9c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=80
author: "<a href='https://twitter.com/FrG_FM'>François-Guillaume Fernandez</a>"
permalink: /choosing-a-new-laptop
---

Whether you have always deferred your laptop selection to local shop salesperson, or you're a professional developer, you may still feel like a colorblind person being asked to choose the red balloon. This article aims at sharing with you **easy ways for an efficient laptop selection**.

![cat-typing](https://media2.giphy.com/media/aNqEFrYVnsS52/giphy.gif?cid=790b76110bc8301ab8d1364278f76e6744830cc3678964af&rid=giphy.gif&ct=g)

First off, so that you don't feel wronged: I'm not a laptop expert and I have never worked for a laptop manufacturer. Nevertheless, I had to purchase laptops for different purposes and different price ranges over the last 10-15 years, and thus I became quite thorough about benchmarking my options. Since I had to recently go through this process again, I thought I'd share how you can easily benchmark and choose the best laptop for your needs without much prior knowledge.


What this article is about:
- main aspects of laptop comparison
- key aspects to easily get the best deal

What this article is not about:
- telling you which laptop to buy right now
- incentivizing products or services of any kind

{% include info.html text="Resources and products shown in this article are used as examples for the selection process, I have no affiliation of any kind with any of these product manufacturers." %}

*Along the way, you will encounter collapsable sections like so :point_down:*

<details>
  <summary>Over here for more details :point_left:</summary>
  
  Those sections are meant for readers who want to dive a bit deeper into the topic, while avoiding information cluttering for casual readers.
</details>

---

## How are we going to compare this

Let's lay down a few things you should be aware of to be methodical here.

### Can't we get everything at once?

You might wonder why I don't want to share THE best laptop of the moment? Well, some of you might have guessed, but just like most consumer products, it's all a matter of balance.

Here we'll consider four main aspects: performance, autonomy, price, weight.

While the last three are self-explanatory, let's elaborate a bit on the first aspect. In this article, "performance" has two sides:
- what produces pure performance: data read/write speed, data processing speed.
- how performance is served to the user: screen, keyboard, touchpad, connectivity slots, etc.

### Processors, hard drive, RAM, what are those?

Performance-wise, the following concepts are very important as they define how you will experience your laptop (taking ages to open a single file :turtle: vs. feeling like your laptop is always waiting on you :sunglasses:).

#### Memory

For computers, memory is a bit too broad of a term: we distinguish storage (things that remains saved even after shutting down your laptop) from RAM (information currently being used by your computer to perform a task at a given moment).

{% include info.html text="RAM stands for Random Access Memory, which isn't very explicit. The French name is more self-explanatory 'mémoire vive' which translates to 'quick/vivacious memory'." %}

##### Storage

To put this into perspective, when using your file explorer, the files that you see are located on your storage device. The information is written in this device so that when powered off, the data prevails. The parallel with human memory would be that storage is where you keep the memory of your first holiday abroad without thinking actively about it. They can be used as external storage devices, and internal ones. Here we focus on the latter[^1], because that's what comes with your laptop.

![kingston-ssd](https://media.kingston.com/kingston/hero/ktc-hero-ssd-a400-m2-lg.jpg)

To compare storage options, consider their storage capacity (measured in Gigabytes/Gb or Gigaoctets/Go) and their read/write speed. To avoid getting a bit too technical, among the two main storage types, HDD (Hard Disk Drive) and SSD (Solid State Drive), SSDs are considerably faster but more expensive.

<details>
  <summary>HDD vs. SSD</summary>

  ![hdd-versus-ssd](https://microage.ca/quebec/wp-content/uploads/sites/56/bb-plugin/cache/hard-drive-ssd-1-landscape.jpg)

  HDD are spinning disks, similar to vinyl record/CD, with two layers: a ferromagnetic layer, where data is stored, and a protective layer. The data interactions are performed by a read/write head (actuator arm), by leveraging the relation between electric current and local magnetic field. They were [introduced by IBM in 1956](https://www.ibm.com/ibm/history/exhibits/storage/storage_350.html).

  For SSDs, forget the spinning disk, each byte of information is written on [MOS transistors](https://en.wikipedia.org/wiki/MOSFET). Thanks to the general trend of transistor density in manufacturing (cf. [Moore law](https://en.wikipedia.org/wiki/Moore%27s_law)), we can now fit quite a lot of those on an integrated circuit. It was first [brought to market by SanDisk in 1991](https://www.computerhistory.org/storageengine/solid-state-drive-module-demonstrated/).
</details>

<details>
  <summary>Fragmentation of a HDD</summary>

  ![defragmentation](https://www.enterprisestorageforum.com/wp-content/uploads/2021/02/fragmentation-understanding-disk-and-ram-fragmentation_6019c77851081.png)

  If you have a HDD and data reading is starting to get slower, you might be experimenting fragmentation. Files that have been repeatedly read or moved, might physically be in a suboptimal order on your physical disk. Since the rotation speed of the disk is limited, fragmentation increases the time needed to access a given file.

  You should consider [defragmenting it](https://www.dummies.com/article/technology/computers/basic-skills/for-seniors-how-to-defragment-your-computer-hard-drive-191687/) (using free software, no rocket science to do on your side).
</details>


##### RAM

![ram](https://www.crucial.fr/content/dam/crucial/dram-products/laptop/images/web/crucial-ddr4-sodimm-kit-w-shadow-image.psd.transform/small-jpg/img.jpg)

RAM could be seen as the maximum immediate capacity to remember information (phone number, etc.). On a computer, you sollicitate the RAM as open more web browser tabs, or applications for instance. In terms of speed, SSDs can't even compete with RAM, but RAM is much more limited in terms of capacity (as of 2022, usually a few Gb or dozens of Gb, while storage capacity is roughly two orders of magnitude larger).


<details>
  <summary>RAM in-depth look</summary>

  Clock cycles: 4800MHz -> 4.8 billion cycles per second

  Column Access Strobe Latency (CL): number of clock cycles it takes for the RAM to respond to a command

  SDR vs. DDR
  ![sdr-ddr](https://www.cgdirector.com/wp-content/uploads/media/2022/03/SDR-vs-DDR-1536x810.jpg)

  DDR generation: DDR4 (1600-3600 MHz), DDR5 (3200-6400 MHz)

  Dual-channel: when your CPU needs to hold data, but your RAM capacity is reached or the RAM speed isn't enough, it will start to use your storage device for this, which is much slower. Enters dual-channel memory to increase the transfer rate between the computer's memory and the CPU. Instead of having a single channel 8Gb RAM connected to your motherboard & thus CPU, having 2 4Gb RAM sticks will have the same RAM capacity as before but double the maximum speed.
  
  
</details>

#### Processing units

Alright, we're now into the core of a computer horsepower: its processing units!

![cpu-vs-gpu](https://www.cgdirector.com/wp-content/uploads/media/2021/05/CPU-vs-GPU-rendering.jpg)

##### CPU

Every personal computers has a Central Processing Unit (CPU). This component has several physical cores, which are all quite powerful (in terms of data processing). The number of physical cores is however limited, so while it can perform multi-tasking, it's optimized for sequential tasks.

![cpu](https://i.insider.com/60402d82b46d720018b04c1d?width=1136&format=jpeg)

<details>
  <summary>Key specifications of a CPU</summary>
  - number of cores & threads: as mentioned previously, the CPU is separated into several physical cores. Each core can have several threads, which are virtual subdivisions of each processing capacity.
  - single-thread performance: how fast a single thread can perform operations
  - clock speed: the number of cycles executed by the CPU each second.
</details>

Comparing multiple CPU models can require some deeper understanding, but fortunately there are multiple online benchmarks that will do the job for you. They always produce an aggregate performance score that you can reliably use for your own comparison. Here is a CPU benchmark website I have used personally: https://www.cpubenchmark.net/

##### GPU

A Graphical Processing Unit (GPU) is optimized for parallel operations. So in 3D rendering or gaming, the computer needs to perform computation for each pixel (position, texture, lighting, etc.). Each of those pixel computation is independent, in the sense, that two neighbouring pixels don't need the RGB value of their neighbour to compute theirs.

![gpu](https://assets2.rockpapershotgun.com/nvidia-rtx-gpu.jpg/BROK/resize/1920%3E/format/jpg/quality/80/nvidia-rtx-gpu.jpg)

If we leave it up to the CPU to do this, as mentioned, the task parallelisation is quite limited. Let's say our CPU can perform 12 tasks at the same time, and our rendering is done for the entire screen resolution, so 1920 x 1080 = 2 073 600  pixel computations for a single frame rendering. A modern GPU can perform several thousands of operations at the same time, that's why it's well suited for this type of tasks.

<details>
  <summary>Key specifications of a GPU</summary>
  - VRAM: you now know that RAM is used for data transfer with the CPU, well VRAM is the same for the GPU. For gamers, as you push your graphics settings of a given game from "minimal" to "ultra", the GPU will need to load more refined textures and elements for each frame and thus need more VRAM.
  - number of cores: I won't get into too much details on this, because depending on the manufacturer and the generation, cores can have several types. They are analog to the physical cores of a CPU, but less powerful.
  - Total Graphics Power (TGP): the power required by the GPU to perform its tasks. A higher value will drain the battery faster, and conversely for the processing throughput.
</details>

Similarly to CPU, GPU are quite complex systems, I highly suggest to use online benchmarks for your own good. I have been using this one for my own needs: https://gpu.userbenchmark.com/

<details>
  <summary>The other lesser known siblings: TPU & IPU</summary>
  - [TPU](https://en.wikipedia.org/wiki/Tensor_Processing_Unit): as deep learning grew bigger in the 2010s, people started looking at GPUs, which were designed for Gaming and 3D rendering, for their own purpose. In 2015, Google developed and started using internally Tensor Processing Units (TPU). Rather than repurposing something designed for video games, they worked on a chip for deep learning, and more generally speaking, tensor processing. You cannot purchase one, but you can experiment with it on [Google Colab](https://colab.research.google.com/github/pytorch/xla/blob/master/contrib/colab/getting-started.ipynb)!
  ![tpu](https://lh3.googleusercontent.com/yl1sHTCh66kLNOVkB7T28J_nh4TyuJdN86rtSnh-HsNiDkbG7U0MHSIjXzotFYY0LHOgGy6ZWhNGqw=e14-rj-sc0xffffff-w1502)
  - [IPU](https://www.graphcore.ai/products/ipu): the company called Graphcore has been developping another chip of their own, called an Intelligence Processing Unit (IPU), which has become gradually known in the machine learning community.
  ![ipu](https://www.graphcore.ai/hs-fs/hubfs/GC010_IPU2_004_W4K-1_compressed.jpg?width=440&name=GC010_IPU2_004_W4K-1_compressed.jpg)
</details>


#### Screen display

Our final stop is the screen, the way you visually experience everything going on inside your laptop. It's actually rather simple, there are three main aspects to consider: screen size, native screen resolution, screen refresh rate.

The screen size is self-explanatory, but depending on your usage, you might have different preferences. Bigger screens are nicer for media and gaming, but the laptop becomes heavier. The current industry usually proposes 3 main otions: 13', 15' or 17' (number of inches along the diagonal of the display).

![screen-resolution](images/screen-resolution.png)

If you have spend a bit of time on video platforms such as YouTube, you may remember the quality settings of videos (1080p, 720p, etc.). Well more broadly, whether it's for a video or a screen, there are a finite number of resolution for 16/9 aspect ratio. As shown in the illustration above, you will find the dominant video quality settings on the market nowadays. 

Why am I showing this? If you're using your laptop for media, and your movies are all in FHD (1080p), going for a laptop with QHD or UHD native resolution will cost you a lot more and won't change anything to your viewing (it might even be worse because the video will be upsampled upon rendering). You get optimal results when your screen **native resolution** matches the resolution of the media you are watching (also applies to gaming). The native resolution is the number of physical pixels on each side of your screen. An UHD screen can render FHD content by upscaling, and in this case the native resolution is UHD, but you can tweak the display resolution to FHD. Also, rendering on UHD is much more demanding than FHD (4 times more information) which requires more computation power.

Alright, what is the refresh rate now? It is the maximum number of times a pixel on your screen will change value per second. What does this mean? A low value like 60Hz might sometimes look like there is some flickering, while high values like 165Hz will look much smoother.

One last thing: especially, if you are using your laptop outside regularly, try to get a matte display. Otherwise the reflection might be disturbing in bright environments with a glossy display. Worth checking the difference over [here](https://www.youtube.com/watch?v=qh7EmbwQU-I).


### Sum-up

#### Data read/write
- storage: what you need to save more files on your computer. There are two types: HDD, and SSD. The latter is more expensive but faster. Whatever the type, the storage capacity ranges between 128Gb and several thousands of Gb.
- RAM: what you need to have more applications opened at the same time. The RAM capacity ranges from 4Gb to several dozens of Gb.

#### Data processing
- CPU: performs operations sequentially using the data stored in RAM, essential to your laptop whatever your usage. You can compare performances on websites such as https://www.cpubenchmark.net/.
- GPU: performs operations in parallel, not essential to your laptop (apart from gaming & other graphics intensive usages). You can compare performances on websites such as https://gpu.userbenchmark.com/.

#### Display
- native resolution: the number of pixels on each side of your screen.
- refresh rate: how many times per second each pixel value can change.


### The different usage types

You can always have multiple usage for your laptop, but I highly suggest you take a second to wonder what you will actually use it for in the coming years. I'll distinguish 4 usage types and lay out how they translate in terms of comparison aspects:
- Gaming: no real concern for autonomy or weight, budget can vary, performance is key
- Media: no real performance requirement, budget should remain low, autonomy, weight and screen quality are key
- Working (software development, presentations, Excel, etc.): flexible budget constraints, performance is important, autonomy & weight are key
- Graphics intensive (deep learning, 3D rendering, etc.): similar to gaming, but performance of GPU is every more important, and autonomy is nice (but rarely compatible)

Now, bear in mind, that you can easily overlap several usage types: in my case, I have been doing deep learning for work.


#### Note: Hardware incompatibility

A few warning notes on hardware constraints depending on your usage type:
- GPU Y/N: Gaming & deep learning usages require a dedicated GPU.
- GPU NVIDIA vs. other: deep learning requires NVIDIA GPU.
- Software development on MAC M1: as of May 2022, MAC M1 chips are starting to be more supported but there are still some unpleasant compatibility issues with this new architecture. If you don't want to spend a lot of time on forums, you might want to avoid that chip architecture for now.
- Storage with HDD or SSD: deep learning requires SSD (if the data is not read fast enough, the GPU will have to wait / stay iddle most of the time).
- RAM minimum capacity: Gaming, Working & Graphics require a lot of RAM (>= 8Gb)

{% include alert.html text="This section is neither exhaustive nor permanently valid, as compatibility improves. If you are reading this more than 1 year after this article was published, use your favorite search engine to confirm." %}


## Benchmark & selection process

### Before buying, why not upgrade?

If you already own a laptop, it might be worth checking if it cannot be upgraded. By upgrading, I mean changing some parts that would have a significant influence on performances.


What you can generally upgrade/replace[^2]:
- RAM: if sometimes your computer freezes temporarily, you might want to switch to a larger RAM capacity.

<details>
  <summary>RAM upgrade details</summary>
  You can also switch to higher clock speed, or switch from single-channel to dual-channel memory to improve performance.
</details>

- Storage: you don't have anymore room on your laptop? You can replace it with a larger one. Transferring or reading data is really slow? You can upgrade your HDD with an SSD.

<details>
  <summary>Storage upgrade details</summary>
  
  Apart from switch from HDD to SSD, there are multiple SSD variants and speed. Check online if you can find a faster version.
</details>

- Battery: if your laptop lasts doesn't last as half as long as it used to, consider replacing the battery.

{% include info.html text="Especially for battery, it is highly recommended to replace it with one that has the same specifications! Search for your model name appended with 'battery'." %}

Whatever the type of modifications you're considering, check whether your model can be upgraded (simple web search, or Youtube search), and if the replacing components are available for sale.

What this section means is that slow data reading, insufficient storage, and dying battery are far from requiring the purchase a new laptop. Please don't buy a new laptop if that's the main reason, replacing a component is significantly cheaper and the planet will be quite thankful :green_heart:


### Narrow down the search scope
Depending on your region, you will not have the same retailing options. Either way, find a trusted website with a lot of laptop options for this section. Here we're trying to find a few good laptop options with minimal investigation time, by using the following criteria:

| Criteria | Options | Recommended |
|-|-|-|
| Screen size | 13', 15', 17' | Up to you |
| Screen resolution | FHD/1080p, QHD/2k, UHD/4k | FHD is enough, the rest is up to you |
| GPU Y/N | None [^3], AMD Radeon, NVIDIA GeForce | Only gaming and graphics really need a GPU. Compatibility-wise, deep learning require NVIDIA products for now. |
| CPU | Intel Core, AMD Ryzen | Whatever fits your budget and gets you the best performance [^4] |
| RAM capacity | 4Gb, 8Gb, 16Gb, 32Gb | >= 8Gb |
| Storage type | HDD, SSD | HDD is you can afford it (it's a must-have for deep learning) |
| Storage capacity | 256Gb, 512Gb, 1T, etc. | >= 512Gb |
| Price | N/A | Up to you |

<details>
  <summary>Integrated vs dedicated graphics</summary>
  
  Modern laptops always have a GPU, but we focus on dedicated GPUs here, which are much more powerful. You can easily recognize this with the brand: NVIDIA (GeForce products) and AMD (Radeon products) are the market leaders on dedicated GPUs, if it's from another brand (like Intel), it's most likely an integrated GPU. Confirm your hunch with a web search :wink:
</details>

Now given your budget, that should already narrow it down to a few laptop models.

### Look closer

Once you've exhausted the search filters, we're going to have to take a closer look?

| Criteria | Options | Recommended |
|-|-|-|
| Battery | 40Wh, 60Wh, 80-90Wh | Compensate for your system consumption: GPUs consume more power, so graphics-intesive users should aim for 60Wh at minimum. |
| Keyboard layout | qwerty, azerty, etc. | depends on your region & spoken language |
| Wifi card | 11ac, 11ax | 11ax is the new, faster generation for Wifi |
| OS compatibility | Windows, MAC, Ubuntu | you'll need Windows for Gaming, the rest is up to you |


### Confirm your choice

Okay, now you should be hesitating between a few laptops. How do you find the best one for you?

Here is a quick checklist:
- check the manufacturer & product line current reputation (if they have very bad reviews and sales, this product line might disappear in the near future)
- compare the CPUs using online benchmarks like https://www.cpubenchmark.net (on the product page, copy paste the CPU model in the search bar of the website)
- if there is one, compare the GPUs using online benchmarks like https://gpu.userbenchmark.com/
- Watch 2-3 **recent** review or comparison videos about those models (only look out for red flags). YouTube channels (e.g. [JarrodsTech](https://www.youtube.com/c/JarrodsTech), [MatthewMoniz](https://www.youtube.com/c/MatthewMoniz1), [LinusTechTips](https://www.youtube.com/c/LinusTechTips)) can be very useful.


### Where to buy it

Congratulations, you found your ideal laptop :clap:
Now to get your hands on it, at the best price, you should check:
- second-hand platforms (who knows, you might be surprised by our brand-new a refurbished product might look, and it's cheaper!)
- manufacturer website (e.g. Dell, Acer, Asus, Apple, HP, Lenovo, Razer, etc.)
- your favorite tech product store's website
- searching for that model on a search engine (yes, really do, you might be able to save a lot with a deal that you missed)

{% include alert.html text="For each laptop model, there might be multiple manufacturer configurations. Ensure that your selection is the same as the one you just benchmarked (or at least as favorable), including the keyboard layout." %}


## A concrete example

I told you I had to go through this process recently right? A good example will better illustrates the previous sections.

### Narrow down the search

Let's start with my personal criteria:

| Criteria | Value |
|-|-|
| Usage | Working & Graphics intensive [^5] |
| Sreen size | 15' |
| Sreen resolution | FHD/1080p [^6] |
| Autonomy | >= 3-4h when not using the GPU |
| Budget | <= 1500€ |
| Keyboard layout | Azerty |
| Storage capacity | >= 512Gb |


The desired usage (deep learning), as mentioned previously, brings about more technical constraints:
- GPU: a powerful NVIDIA mobile GPU, of recent generations (RTX 20 or 30), with VRAM >= 6Gb.
- CPU: a powerful CPU, either an Intel Core 12th gen (>= i5) or 11th gen(>= i7), or an AMD Ryzen 6k series (>=5) or 5k series(>= 7).
- RAM capacity: >= 16Gb
- Storage type: SSD

I live in France, so I use the following websites for my initial search:
- https://www.ldlc.com/
- https://www.fnac.com/
- https://www.cdiscount.com/
- https://www.amazon.fr/

After setting those filters, here is what I ended up with in May 2022:
- Acer Nitro 5
- Acer Predator Helios 300
- Asus Dash
- Dell G15
- Lenovo Legion 5i
- MSI GF66

{% include info.html text="Quick advice: if you put the price as a filter, add 20-30% in your filter, because there might be discounts on other retailing websites." %}


### Take a closer look

So this means that for my budget, in my region, the following brands should be my focus: Acer, Asus, Dell, Lenovo, MSI 
Investigating a bit with my criteria that don't fit in a search filter:

| Criteria | Value |
|-|-|
| RAM dual channel Y/N | Y |
| Battery | >= 60Wh |
| Keyboard layout | azerty :fr: |
| Wifi card | >= 11ac |
| OS compatibility | Ubuntu |

https://www.youtube.com/watch?v=Bq1NPvqI91w
--> Nitro 5 & Acer Helios (GPU, RAM & screen quality)
--> MSI terrible battery

laptops:
- dell g15 5520
- lenovo legion 5i


### Final showdown

versus comparison: - https://www.youtube.com/watch?v=kRjyxh9AG1w
165Hz is much better, wifi much faster on G15, battery better on G15, similar in terms of GPU perf, similar very good laptops

Let's gather up all the important information and add the [CPU Mark](https://www.cpubenchmark.net/compare/Intel-i7-12700H-vs-Intel-i7-11800H-vs-Intel-i5-12500H/4721vs4358vs4750) using online benchmarks.

| | Dell G15 5520 | Lenovo Legion 5i (6th gen) | Lenovo Legion 5i (7th gen) |
|-|-|-|-|
|Price| 1499€ | 1399€ | 1499€|
|CPU| Intel Core i7 12700H | Intel Core i7 11800H | Intel Core i5 12500H|
|CPU Mark| 27642 | 21317 | 23224 |
|GPU| NVIDIA RTX 3060 | NVIDIA RTX 3060 | NVIDIA RTX 3060|
|Screen| FHD, 165Hz | FHD, 120Hz | FHD, 165Hz|
|Storage| SSD, 512Go | SSD, 512Go | SSD, 512Go|
|RAM| 16Go 4800MHz, dual channel | 16Go, 3200Mhz, single channel | 16Go 4800Mhz, dual channel|
|Wifi| 11ax | 11ax | 11ac|
|Battery| 86Wh (6 cells) | 60Wh (4 cells) | 80Wh (4 cells)|
|Weight| 2.6kg | 2.4kg | 2.4kg |

The screen refresh rate, RAM and battery kick out the Lenovo 6th gen.

Let's know only keep the specs that are different:


| | Dell G15 5520 | Lenovo Legion 5i (7th gen) |
|-|-|-|
|CPU Mark| 27642 | 23224 |
|Wifi| 11ax | 11ac|
|Battery| 86Wh (6 cells) | 80Wh (4 cells)|

On those 3 aspects, the Dell G15 is superior, so that will be my pick!


### Confirm the choice

Let's run down the checklist:
- Dell is an established & reputed laptop manufacturers, and the reviews are excellent
- the CPU is actually the best mobile CPU on the market at the moment (May 2022)
<details>
  <summary>Intel Core 11th and 12th gen</summary>
  {% include youtube.html content='https://www.youtube.com/embed/i9Dy_1SSw2U' %}
  You may have noticed the difference in CPU Mark between the i7 11800H (11th gen) and i5 12500H (12th gen), which is only an i5. With their new generation of CPUs, Intel is aiming at power efficiency. Remember the physical cores of the CPU? Now your chip will onboard two types: P-cores (performance), and E-cores (efficiency). The appropriate core type will be selected dynamically to get you the best performance/battery life balance.
</details>

- the GPU is among the best ranked mobile GPUs
<details>
  <summary>Compare with your previous laptop</summary>
  Out of safety, I [compared the performances](https://gpu.userbenchmark.com/Compare/Nvidia-RTX-3060-Laptop-vs-Nvidia-RTX-2070-Mobile-Max-Q/m1452971vsm703511) of this GPU with my last profesionnal laptop, a Razer Blade 15, NVIDIA RTX 2070 Max Q. It outperforms it between 8 and 12% on all aspects, while the price being much lower (1499€ for the Dell G15, while the Razer Blade was 2200€ and the end of 2020 when it was purchased). I did the comparison because performance-wise, I was very happy with that previous laptop.
</details>

- let's check a few laptop reviews:

{% include youtube.html content='https://www.youtube.com/embed/Ej_mgN25a_I' %}
Takeaways:
- SSD & RAM are upgradable
- very good value for money in terms of perf thanks to 12th gen Intel CPU
- very good screen quality
- incredible battery

{% include youtube.html content='https://www.youtube.com/embed/m5to9qZwaDk' %}
Takeaways:
- the laptop is a bit heavy
- very nice screen
- good keyboard
- best battery on the market

<details>
  <summary>How to upgrade the SSD</summary>
  {% include youtube.html content='https://www.youtube.com/embed/o-Z9JV4f4K0' %}
</details>

<details>
  <summary>MUX Switch</summary>
  
  So this is a concept I discovered while benchmarking a few weeks back, an quite an interesting one, especially if you're using your laptop for Gaming!

  {% include youtube.html content='https://www.youtube.com/embed/6mWies_4oDs' %}

  Laptops may or may not have a MUX switch, which a feature that can bypass the iGPU when data flows from the dGPU to your screen. What does that mean?
  - MUX Switch ON: data processed on dGPU, then directly displayed on screen.
  - MUX Switch OFF: data processed on dGPU, then processed by iGPU, then displayed on screen.

  Having a MUX switch gives you the choice. But when it's on, you get better FPS in games, at the cost of higher power/battery consumption.
  
</details>

No red flags, so the choice is confirmed!


## Final tips to get the best out of your laptop

### Help your heat management hardware
Your laptop CPU & GPU produce heat, while is contained by the cooling system. The key to this cooling process are your laptop fans, when speed up whenever the measured internal temperature gets higher. When you put your laptop on cloth, your coach, or any other fan-obstructing surface, as it's partially obstructed, your fans will speed up even more. This has two consequences:
- reducing the life of your fans (they will operate much faster than without obstruction for the same usage)
- endangering internal components (if the temperatures are too high, that will degrade hardware prematurely)

What can you do for this?
Two things:
- consider purchasing a laptop stand (or at least not obstructing the fans on a regular basis): the laptop will last longer, and your neck will thank you for it.
- clean it once in a while: it's inevitable that dust will get in the way of your air entries at some point. Check online how to safely clean your fans.

### A good night sleep for everyone
When you go to bed, consider shutting down your laptop instead of clapping it/putting it to sleep. Simply put, while in sleep mode, your hardware is sollicitated more than when shut down (remember, it's not shut down so the RAM is loaded with data among others). If you put it to sleep, that will reduce its life expectancy.

### Minimizing the number of charge cycles

While there are still arguments in favour or against it in the community, keeping your laptop plugged even when it's not needed is a risk. Some people say that leaving it plugged won't damage the battery well-being (same debate with smartphones), some say the opposite. I am no expert in charger and laptop battery manufacturing, but why take the risk?

When plugged, you sollicitate:
- your laptop charger, which could certainly benefit from not being powered on all the time
- your laptop battery: rule of thumb, since we don't know for sure, if you don't need max perf and have a lot of battery, unplug it :+1:


[^1]:both serve the same function. But external drives are usually used for backups and extra file storage, while internal ones, on top of static files, also hold your operating system files (e.g. Windows, MAC, Ubuntu, etc.).
[^2]:some manufacturers, like Apple, don't let people easily tweak the inside of their laptops.
[^3]:modern laptops will have an integrated GPU (iGPU), when they don't have a dedicated GPU (dGPU). Usually the iGPU brand is the same as the CPU's manufacturer.
[^4]:note: CPU generation is very important. For instance, Intel Core i5 12th gen >= i7 11th gen.
[^5]:I would be using it for Deep Learning more specifically.
[^6]:corresponds to 1920 by 1080 pixels, also called FHD (Full High Definition).

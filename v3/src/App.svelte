<svelte:options customElement="test-tag" />

<div class="absolute bottom-0 right-0 shadow-2xl w-[25vw]">
  <!-- Component: Basic lg sized tab -->
  <!-- svelte-ignore a11y_role_supports_aria_props_implicit -->
  <section class="max-w-full" aria-multiselectable="false">
    <ul class="flex items-center border-b border-slate-200" role="tablist">
      <li role="presentation">
        <button
          class="inline-flex items-center justify-center w-full h-12 gap-2 px-6 -mb-px text-sm font-medium tracking-wide transition duration-300 border-b-2 rounded-t focus-visible:outline-none whitespace-nowrap border-emerald-500 hover:border-emerald-600 focus:border-emerald-700 text-emerald-500 hover:text-emerald-600 focus:text-emerald-700 hover:bg-emerald-50 focus:bg-emerald-50 disabled:cursor-not-allowed disabled:border-slate-500 stroke-emerald-500 hover:stroke-emerald-600 focus:stroke-emerald-700"
          id="tab-label-1a"
          role="tab"
          aria-setsize="3"
          aria-posinset="1"
          tabindex="0"
          aria-controls="tab-panel-1a"
          aria-selected="true"
        >
          <span>Tab 1</span>
        </button>
      </li>
      <li role="presentation">
        <button
          class="inline-flex items-center justify-center w-full h-12 gap-2 px-6 -mb-px text-sm font-medium tracking-wide transition duration-300 border-b-2 border-transparent rounded-t focus-visible:outline-none justify-self-center hover:border-emerald-500 focus:border-emerald-600 whitespace-nowrap text-slate-700 stroke-slate-700 hover:bg-emerald-50 hover:text-emerald-500 focus:stroke-emerald-600 focus:bg-emerald-50 focus:text-emerald-600 hover:stroke-emerald-600 disabled:cursor-not-allowed disabled:text-slate-500"
          id="tab-label-2a"
          role="tab"
          aria-setsize="3"
          aria-posinset="2"
          tabindex="-1"
          aria-controls="tab-panel-2a"
          aria-selected="false"
        >
          <span>Tab 2</span>
        </button>
      </li>
      <li role="presentation">
        <button
          class="inline-flex items-center justify-center w-full h-12 gap-2 px-6 -mb-px text-sm font-medium tracking-wide transition duration-300 border-b-2 border-transparent rounded-t focus-visible:outline-none justify-self-center hover:border-emerald-500 focus:border-emerald-600 whitespace-nowrap text-slate-700 stroke-slate-700 hover:bg-emerald-50 hover:text-emerald-500 focus:stroke-emerald-600 focus:bg-emerald-50 focus:text-emerald-600 hover:stroke-emerald-600 disabled:cursor-not-allowed disabled:text-slate-500"
          id="tab-label-3a"
          role="tab"
          aria-setsize="3"
          aria-posinset="3"
          tabindex="-1"
          aria-controls="tab-panel-3a"
          aria-selected="false"
        >
          <span>Tab 3</span>
        </button>
      </li>
    </ul>
    <div>
      <div
        class="px-6 py-4"
        id="tab-panel-1a"
        aria-hidden="false"
        role="tabpanel"
        aria-labelledby="tab-label-1a"
        tabindex="-1"
      >
        <div>
          <ul
            aria-label="Nested user feed"
            role="feed"
            class="relative flex flex-col gap-12 py-12 pl-8 before:absolute before:top-0 before:left-8 before:h-full before:border before:-translate-x-1/2 before:border-slate-200 before:border-dashed after:absolute after:top-6 after:left-8 after:bottom-6 after:border after:-translate-x-1/2 after:border-slate-200"
          >
            <li role="article" class="relative pl-8">
              <div class="flex flex-col flex-1 gap-4">
                <a
                  href="#?"
                  class="absolute z-10 inline-flex items-center justify-center w-8 h-8 text-white rounded-full -left-4 ring-2 ring-white"
                >
                  <img
                    src="https://i.pravatar.cc/48?img=1"
                    alt="user name"
                    title="user name"
                    width="48"
                    height="48"
                    class="max-w-full rounded-full"
                  />
                </a>
                <h4
                  class="flex flex-col items-start text-lg font-medium leading-8 lg:items-center md:flex-row text-slate-700"
                >
                  <span class="flex-1"
                    >Mary Jane<span
                      class="text-base font-normal text-slate-500"
                    >
                      created a new thread</span
                    ></span
                  ><span class="text-sm font-normal text-slate-400">
                    3 hours ago</span
                  >
                </h4>
                <p class=" text-slate-500">
                  We just released windUI v1.5, which includes a brand new
                  component. An activity feed is a chronological record of
                  system events or user actions. Have a look at the feed page
                  and let me know what you think. Feedback is highly
                  appreciated.
                </p>
              </div>
            </li>
            <li role="article" class="relative pl-8">
              <div class="flex flex-col flex-1 gap-4">
                <a
                  href="#?"
                  class="absolute z-10 inline-flex items-center justify-center w-8 h-8 text-white rounded-full -left-4 ring-2 ring-white"
                >
                  <img
                    src="https://i.pravatar.cc/48?img=12"
                    alt="user name"
                    title="user name"
                    width="48"
                    height="48"
                    class="max-w-full rounded-full"
                  />
                </a>
                <h4
                  class="flex flex-col items-start text-lg font-medium leading-8 lg:items-center md:flex-row text-slate-700"
                >
                  <span class="flex-1"
                    >John langan <span
                      class="text-base font-normal text-slate-500"
                    >
                      💚 liked the thread
                    </span></span
                  ><span class="text-sm font-normal text-slate-400">
                    2 hours ago</span
                  >
                </h4>
              </div>
              <ul
                role="group"
                class="relative flex flex-col gap-12 py-12 pl-6 lg:pl-8 after:absolute after:top-12 after:left-6 lg:after:left-8 after:bottom-12 after:border after:-translate-x-1/2 after:border-slate-200 before:absolute before:top-6 before:left-6 lg:before:left-8 before:bottom-6 before:border before:-translate-x-1/2 before:border-slate-200 before:border-dashed"
              >
                <li role="article" class="relative pl-6 lg:pl-8">
                  <div class="flex flex-col flex-1 gap-4">
                    <a
                      href="#?"
                      class="absolute z-10 inline-flex items-center justify-center w-8 h-8 text-white rounded-full -left-4 ring-2 ring-white"
                    >
                      <img
                        src="https://i.pravatar.cc/48?img=1"
                        alt="user name"
                        title="user name"
                        width="48"
                        height="48"
                        class="max-w-full rounded-full"
                      />
                    </a>
                    <h4
                      class="flex flex-col items-start text-lg font-medium leading-8 lg:items-center md:flex-row text-slate-700"
                    >
                      <span class="flex-1"
                        >Mary Jane <span
                          class="text-base font-normal text-slate-500"
                        >
                          replied
                        </span></span
                      ><span class="text-sm font-normal text-slate-400">
                        2 hours ago</span
                      >
                    </h4>
                    <p class=" text-slate-500">
                      Hey john! Did you had a look at the new component?
                    </p>
                  </div>
                </li>
                <li role="article" class="relative pl-6 lg:pl-8">
                  <div class="flex flex-col flex-1 gap-4">
                    <a
                      href="#?"
                      class="absolute z-10 inline-flex items-center justify-center w-8 h-8 text-white rounded-full -left-4 ring-2 ring-white"
                    >
                      <img
                        src="https://i.pravatar.cc/48?img=12"
                        alt="user name"
                        title="user name"
                        width="48"
                        height="48"
                        class="max-w-full rounded-full"
                      />
                    </a>
                    <h4
                      class="flex flex-col items-start text-lg font-medium leading-8 lg:items-center md:flex-row text-slate-700"
                    >
                      <span class="flex-1"
                        >John langan <span
                          class="text-base font-normal text-slate-500"
                        >
                          replied
                        </span></span
                      ><span class="text-sm font-normal text-slate-400">
                        2 hours ago</span
                      >
                    </h4>
                    <p class=" text-slate-500">
                      It looks awesome! Good one! The only thing that I would
                      tweak is the spacing in smaller screens. Other than that
                      it looks superb! Really loved the color as well.
                    </p>
                  </div>
                </li>
                <li role="article" class="relative pl-6 lg:pl-8">
                  <div class="flex flex-col flex-1 gap-4">
                    <a
                      href="#?"
                      class="absolute z-10 inline-flex items-center justify-center w-8 h-8 text-white rounded-full -left-4 ring-2 ring-white"
                    >
                      <img
                        src="https://i.pravatar.cc/48?img=1"
                        alt="user name"
                        title="user name"
                        width="48"
                        height="48"
                        class="max-w-full rounded-full"
                      />
                    </a>
                    <h4
                      class="flex flex-col items-start text-lg font-medium leading-8 lg:items-center md:flex-row text-slate-700"
                    >
                      <span class="flex-1"
                        >Mary Jane <span
                          class="text-base font-normal text-slate-500"
                        >
                          replied
                        </span></span
                      ><span class="text-sm font-sm text-slate-400">
                        3 hours ago</span
                      >
                    </h4>
                    <p class=" text-slate-500">
                      Thanks so much 🙏. Your feedback is highly appreciated.
                    </p>
                  </div>
                </li>
              </ul>
            </li>
            <li role="article" class="relative pl-8">
              <div class="flex flex-col flex-1 gap-4">
                <a
                  href="#?"
                  class="absolute z-10 inline-flex items-center justify-center w-8 h-8 text-white rounded-full -left-4 ring-2 ring-white"
                >
                  <img
                    src="https://i.pravatar.cc/48?img=13"
                    alt="user name"
                    title="user name"
                    width="48"
                    height="48"
                    class="max-w-full rounded-full"
                  />
                </a>
                <h4
                  class="flex flex-col items-start text-lg font-medium leading-8 lg:items-center md:flex-row text-slate-700"
                >
                  <span class="flex-1"
                    >Manos Gaitanakis<span
                      class="text-base font-normal text-slate-500"
                    >
                      commented</span
                    ></span
                  ><span class="text-sm font-normal text-slate-400">
                    3 hours ago</span
                  >
                </h4>
                <p class=" text-slate-500">
                  Love it! I really like how the nested feeds are working as
                  well. Is that going to be multi-nested? Or maybe stay in just
                  one level. Also any ides on how I can remove the time stamp
                  from the feeds?
                </p>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div
        class="hidden px-6 py-4"
        id="tab-panel-2a"
        aria-hidden="true"
        role="tabpanel"
        aria-labelledby="tab-label-2a"
        tabindex="-1"
      >
        <p>
          One must be entirely sensitive to the structure of the material that
          one is handling. One must yield to it in tiny details of execution,
          perhaps the handling of the surface or grain, and one must master it
          as a whole.
        </p>
      </div>
      <div
        class="hidden px-6 py-4"
        id="tab-panel-3a"
        aria-hidden="true"
        role="tabpanel"
        aria-labelledby="tab-label-3a"
        tabindex="-1"
      >
        <p>
          Even though there is no certainty that the expected results of our
          work will manifest, we have to remain committed to our work and
          duties; because, even if the results are slated to arrive, they cannot
          do so without the performance of work.
        </p>
      </div>
    </div>
  </section>
  <!-- End Basic lg sized tab -->
</div>

<style lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>

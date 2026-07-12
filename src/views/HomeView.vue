<template>
    <div class="jumbotron bg-transparent mb-0 radius-0">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h1 class="main-title">./Cyber.Armourscope</h1>
                    <div class="lead mb-3 text-mono text-success sub-title">Cyber Security Consulting and Services.</div>
                </div>
            </div>
            <div class="row">
                <div class="col-xl-6 order-2 order-xl-1">
                    <p class="mt-5 text-grey text-spacey">
                        Armourscope is committed to delivering tailored cyber security services including Vulnerability Analysis and Red Teaming.
                    </p>
                    <p class="mt-5 text-grey text-spacey">
                        Armourscope provides one-off consultation for businesses. Including threat surface analysis and reporting. Ongoing services include Red Teaming
                        practices to help secure your environment, and regular consultation to grow your cyber security team with the Armourscope mindset.
                    </p>
                    <br />
                    <h3>About Us.</h3>
                    <p class="mt-5 text-grey text-spacey">We're a dynamic team with 10+ years experience in the industry. With multi-platform expertise including *nix, windows and embedded.</p>
                    <pre>
                        <code>
                            # Begin
                            def ArmourScope():

                        </code>
                    </pre>
                </div>
                <div class="col-xl-6 order-1 order-xl-2">
                    <div class="row mt-3 mt-xl-5">
                        <div class="col-6 mb-3 mb-xl-4">
                            <div class="terminal-panel text-mono">
                                <div class="terminal-panel-header">
                                    <span class="terminal-dot dot-red"></span>
                                    <span class="terminal-dot dot-orange"></span>
                                    <span class="terminal-dot dot-green"></span>
                                    <a href="https://docs.armourscope.com" class="terminal-panel-title text-light">
                                        <span class="fas fa-book mr-1 text-success"></span>./docs
                                    </a>
                                </div>
                                <div class="terminal-panel-body">
                                    <p class="terminal-panel-desc text-grey d-none d-md-block">
                                        Guides, reports and reference material for working with Armourscope.
                                    </p>
                                    <ul class="list-unstyled mb-0">
                                        <li><a href="#" class="text-success"><span class="prompt">&gt;</span> Getting started</a></li>
                                        <li><a href="#" class="text-success"><span class="prompt">&gt;</span> Engagement process</a></li>
                                        <li><a href="#" class="text-success"><span class="prompt">&gt;</span> Reporting format</a></li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3 mb-xl-4">
                            <div class="terminal-panel text-mono">
                                <div class="terminal-panel-header">
                                    <span class="terminal-dot dot-red"></span>
                                    <span class="terminal-dot dot-orange"></span>
                                    <span class="terminal-dot dot-green"></span>
                                    <span class="terminal-panel-title text-light">
                                        <span class="fas fa-shield-alt mr-1 text-success"></span>./capabilities
                                    </span>
                                </div>
                                <div class="terminal-panel-body">
                                    <p class="terminal-panel-desc text-grey d-none d-md-block">
                                        Services we deliver to secure your environment.
                                    </p>
                                    <ul class="list-unstyled mb-0">
                                        <li><span class="prompt text-success">&gt;</span> Vulnerability Analysis</li>
                                        <li><span class="prompt text-success">&gt;</span> Red Teaming</li>
                                        <li><span class="prompt text-success">&gt;</span> Threat Surface Analysis</li>
                                        <li><span class="prompt text-success">&gt;</span> Security Consulting</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* Terminal-window styled panels, using the neon-glow theme palette:
   body #0c0d16, card slate #32334a, borders #151623/#28293e, success #17b06b */
.terminal-panel {
    height: 100%;
    background-color: #1a1b2b;
    border: 1px solid #28293e;
    border-radius: 6px;
    overflow: hidden;
}

.terminal-panel-header {
    display: flex;
    align-items: center;
    padding: 0.4rem 0.75rem;
    background-color: #32334a;
    border-bottom: 1px solid #151623;
    font-size: 0.85rem;
    white-space: nowrap;
}

.terminal-panel-title {
    margin-left: 0.5rem;
    letter-spacing: 0.03em;
}

a.terminal-panel-title:hover {
    color: #17b06b !important;
    text-decoration: none;
}

.terminal-dot {
    width: 8px;
    height: 8px;
    border-radius: 50%;
    margin-right: 4px;
    flex-shrink: 0;
}

.dot-red {
    background-color: #ff3c5c;
}

.dot-orange {
    background-color: #f97515;
}

.dot-green {
    background-color: #17b06b;
}

.terminal-panel-body {
    padding: 0.75rem;
    font-size: 0.8rem;
}

.terminal-panel-desc {
    font-size: 0.75rem;
    margin-bottom: 0.5rem;
}

.terminal-panel-body li {
    margin: 0.35rem 0;
}

.prompt {
    margin-right: 0.25rem;
}

/* Phones: tighter still — dots and descriptions go, text shrinks */
@media (max-width: 767.98px) {
    .terminal-dot {
        display: none;
    }

    .terminal-panel-title {
        margin-left: 0;
    }

    .terminal-panel-header {
        padding: 0.3rem 0.5rem;
        font-size: 0.72rem;
    }

    .terminal-panel-body {
        padding: 0.5rem;
        font-size: 0.68rem;
    }

    .terminal-panel-body li {
        margin: 0.25rem 0;
    }
}
</style>

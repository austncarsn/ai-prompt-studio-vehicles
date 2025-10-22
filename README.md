
2. Open the `index.html` file in your browser:
- Double-click the file, or
- Use a local server like Live Server in VS Code for best performance (avoids CORS issues with local files).

That's it! No build steps or package managers needed.

*(back to top)*

## Usage

1. **Configure Your Scene**:
- Select a car make (e.g., Porsche, Tesla) and model from the dropdowns.
- Choose colors, scene types (e.g., Mountain Road, Cyberpunk City), camera movements, lighting, weather, and film styles.
- Toggle additional elements like reflections, motion blur, or slow motion for enhanced details.

2. **Generate Prompt**:
- Click "Generate Prompt" to create a unique, cinematic description. Prompts vary based on a seed for freshness.
- View word/character counts and the full output in the right panel.

3. **Interact and Save**:
- Copy the prompt to your clipboard for use in AI tools.
- Save/load presets via modals (stored in browser LocalStorage).
- Browse recent prompts or randomize all settings for quick ideation.
- Simulate API sending (extendable for real integrations).

Example Generated Prompt:
> Hyper-detailed explosive action sweeping view capturing a elegant racing red Porsche 911 GT3 racing fiercely along the Desert Highway clear skies terrain golden hour illumination, incorporating mirror-like surface gleams and polished accents, trailing velocity streaks for velocity emphasis. Emphasize aggressive aerodynamic lines, road adhesion physics, and ecosystem fusion through god rays and atmospheric particles. Deliver in ultra-high-definition clarity, evoking premium visual effects mastery, enhanced by intense pursuits, heroic angles, and orchestral swells.

For advanced users: Edit the JavaScript in `<script>` tags to customize prompt templates or integrate real API calls (e.g., to OpenAI).

*(back to top)*

## Features

- **Dynamic Prompt Generation**: Combines user inputs with randomized elements for non-repetitive, vivid descriptions.
- **Preset Management**: Save, load, and delete configurations for reusable setups.
- **Recent History**: Track up to 6 recent prompts with timestamps and quick-load buttons.
- **Responsive Design**: Mobile-friendly grid layout with glassmorphism cards and gradient borders.
- **Accessibility**: ARIA labels, semantic HTML, and reduced-motion support.
- **Performance Optimizations**: Hardware acceleration (`transform: translateZ(0)`), minimal JS footprint, and smooth animations.
- **Customization Hooks**: Easy to extend for other themes (e.g., space or historical scenes) by modifying arrays in JS.

*(back to top)*

## Roadmap

See the [open issues](https://github.com/yourusername/ai-vehicle-prompt-studio/issues) for a list of proposed features (and known issues).

- [ ] Integrate real API endpoints (e.g., OpenAI Sora via user-provided keys).
- [ ] Add export options (JSON, TXT for prompts).
- [ ] Expand car database with more makes/models (user contributions welcome).
- [ ] Theme switcher (dark mode, retro aesthetics).
- [ ] Prompt validation and length controls.
- [ ] Multi-language support for global users.

*(back to top)*

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

Please include tests for new features and discuss major changes via issues first.

*(back to top)*

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

*(back to top)*

## Contact

Austin Carson

Project Link: [https://github.com/yourusername/ai-vehicle-prompt-studio](https://github.com/yourusername/ai-vehicle-prompt-studio)

*(back to top)*

## Acknowledgments

- [Alpine.js](https://alpinejs.dev/) and [Tailwind CSS](https://tailwindcss.com/) for powering the interactivity and design.
- Inspiration from AI prompt engineering communities and tools like Midjourney/Sora.
- Thanks to the open-source contributors who've shaped modern web development.

*(back to top)*

# MetaMask-Name-Generator
MetaMask Name Generator

function generateMetaMaskName() {
    const prefixes = ["Crypto", "Blockchain", "Ether", "Token", "Web3", "Decentral", "Chain", "Meta"];
    const suffixes = ["Master", "Hacker", "Wizard", "Explorer", "Guru", "Shifter", "Ninja", "King", "Queen", "Kingdom", "Whale"];
    const randomPrefix = prefixes[Math.floor(Math.random() * prefixes.length)];
    const randomSuffix = suffixes[Math.floor(Math.random() * suffixes.length)];
    
    return `${randomPrefix} ${randomSuffix}`;
}

// Generate and display the name
console.log(generateMetaMaskName()); 
857
